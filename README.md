## <div style="text-align: Center"> Perfil dos candidatos a prefeito no Brasil </div>

##### <div style="text-align: right"> Autor: Adma Raia</div>


## <div style="text-align: justify"> Motivação</div> 


#### <div style="text-align: justify"> A eleição é um instrumento importante para a manutenção do sistema democrático, assim como, para o desenvolvimento sócio-econômico do país. Logo, a geração de informações e conhecimento neste setor, contribui para que o cidadão tenha consciência do seu papel no sistema político, tomando decisões mais assertivas. </div>

#### <p> <div style="text-align: justify"> Recentemente os brasileiros participaram de mais um pleito para prefeito em todo território nacional, e ao observar o desenrolar das campanhas eleitorais, o comportamento dos candidatos, a falta de aderência entre o discurso da campanha eleitoral e a atuação dos mesmos após a eleição, entre outros, despertaram meu interesse em buscar os dados públicos dos candidatos (tse.gov.br) e traçar o perfil dos candidatos a prefeito em todo o país. </div></p>


## <div style="text-align: justify"> Objetivo</div> 
#### <p> <div style="text-align: justify"> Aplicar técnicas de mineração de dados e aprendizado de máquina para as campanhas eleitorais para prefeito no período entre 2010 e 2020, para:
  <ul>
  <li> identificar o perfil dos candidatos a prefeito no país;
  <li> avaliar a relação entre o perfil do candidato e a conquista do pleito;
  <li> analisar os perfis dos candidatos de acordo com as Regiões Brasileiras; 
  <li> elaborar modelo preditivo com base no perfil do candidato, para indicar a “probabilidade” de  sucesso por Região do país.
  </ul>
  </div></p>
  
  
  ## <div style="text-align: justify"> Dados </div> 
 #### <p> <div style="text-align: justify"> A fonte primária dos dados é o [Repositório de dados Eleitorais do TSE](https://www.tse.jus.br/eleicoes/estatisticas/repositorio-de-dados-eleitorais-1).</div></p>
 ####  <p> <div style="text-align: justify">Os arquivos com os dados dos candidatos nos anos de 2012, 2016 e 2018 foram baixados do repositório do TSE, realizada a limpeza e integração dos datasets, deixando apenas os dados referentes aos candidatos a prefeito aptos. O arquivo base para as demais fases do trabalho é [base_20122020.xls](https://github.com/admaraia/PerfilCandPrefeito-Brasil/blob/main/base_20122020.xlsx) disponível neste repositório.</div></p>
 
 ## <div style="text-align: justify"> Métodos </div> 
 ####  <p> <div style="text-align: justify"> O tratamento/transformação do dataset foi realizado no notebook [tratamento_dados.ipynb](https://github.com/admaraia/PerfilCandPrefeito-Brasil/blob/main/tratamento_dados.ipynb). Foram seguidas as etapas abaixo:
 <ul>
  <li> eliminação colunas (classes) vazias;
  <li> identificação dos tipos dos dados (qualitativo ordinal/nominal, quantitativo discreto);
  <li> limpeza de dados duplicados;
  <li> criação da classe faixa etária de acordo utilizando a classificação do IBGE;
  <li> criação da classe que integra cidade de nascimento com cidade onde foi registrada a candidatura;
  <li> criação da classe que informa se a candidatura foi realizada com coligação partidária ou não;
  <li> identificação e tratamento de dados nulos;
  <li> exportação do database tratado (base_Brasil.csv).
  </ul> </div></p>
  
 #### <p> <div style="text-align: justify"> A análise exploratória (EDA) do dataset foi realizado no notebook [analise_exploratoria_final.ipynb](https://github.com/admaraia/PerfilCandPrefeito-Brasil/blob/main/analise_exploratoria_final.ipynb). Foram seguidas as etapas abaixo:
 <ul>
  <li> explorar o dataset buscando responder:
    <ul>
     <li> Como é a distribuição dos candidatos por Gênero no país?
     <li> Qual a Região que registrou o maior número de candidatas mulheres?
     <li> Como é a distribuição dos candidatos por Raça no país?
     <li> Qual é o grau de instrução dos candidatos?
     <li> Qual a faixa etária predominante entre os candidatos?
     <li> Existe alguma região que aprensenta discrepância entre das características Raça, Gênero, Faixa etária e escolaridade no país?
     <li> Existe diferença entre os perfis dos candidatos quando separamos por gênero?
    </ul>
  <li> Com base nas respostas dos itens acima, foi realizado mais um tratamento no dataset (detalhado no notebook) para aplicar no modelo machine learning para classificar o perfil dos candidatos;
  </ul> </div></p>
  
  #### <p> <div style="text-align: justify"> Nesta etapa foram utilizadas técnicas de machine learning para implementar um <b> modelo de classificação </b> para o perfil de candidado, o qual partindo do input de perfil ele será classificado como Eleito ou Não Eleito. Os testes e o todo o processo de implementação e avaliação do modelo foi realizada no notebook [modelagem_classPerfil.ipynb](https://github.com/admaraia/PerfilCandPrefeito-Brasil/blob/main/modelagem_classPerfil.ipynb). As etapas da implementação do modelo preditivo foram:
  
 <ul>
  <li> xxxx;
  <li> xs;
  <li> yyyyy.
  </ul> </div></p>
  
## <div style="text-align: justify"> Resultados e Conclusões </div> 

#### De acordo com os resultados o perfil dos candidatos a prefeito no Brasil é xxxxxxxxxxxxxxxxxxxxxxxxx, identificamos que há diferença nas características do perfil quanto ao gênero, sendo o perfil xxxxx masculino e yyyyyy feminino.

#### Foram observadas discrepâncias entre as regiões do país xxxxxx e xxxxxx. Considerando que as regiões mais populosas são NE e SE, as quais apresentam um peso maior quando analisamos um perfil geral do país.

####  Os modelos de ***classificação*** utilizados foram xxxx e yyyyy, que apresentam as métricas cccc e ddddd, logo foi escolhido o resultado o melhor xxxxxx que produz um bom resultado quando analisado com as demais informações geradas.

####  A partir do modelo de classificação, foi implementado a componente preditiva, objetivando indentificar a probalidade de um perfil obter sucesso no pleito para prefeito. As características do modelo são apresentadas abaixo, assim como as avaliações.

#### A parti das das etapas descritas acima foi possível partir de um conjunto de dados disponível no site do governo federal, tratar os dados, analisar e gerar informações para a sociedade sobre o perfil dos candidatos a prefeito no país. Assim, como foi possível implementar uma ferramenta (modelo preditivo) baseada em dados, que ao inserir informações a respeito do seu perfil é informa a probabilidade de sucesso no pleito para prefeito.
 
