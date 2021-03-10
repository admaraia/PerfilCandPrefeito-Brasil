## <div style="text-align: Center"> Perfil dos candidatos a prefeito no Brasil </div>

##### <div style="text-align: right"> Autor: Adma Raia</div>


## <div style="text-align: justify"> Motivação</div> 


#### <div style="text-align: justify"> A eleição é um instrumento importante para a manutenção do sistema democrático, assim como, para o desenvolvimento sócio-econômico do país. Logo, a geração de informações e conhecimento neste setor, contribui para que o cidadão tenha consciência do seu papel no sistema político, tomando decisões mais assertivas. </div>

#### <p> <div style="text-align: justify"> Recentemente os brasileiros participaram de mais um pleito para prefeito em todo território nacional, e ao observar o desenrolar das campanhas eleitorais, o comportamento dos candidatos, a falta de aderência entre o discurso da campanha eleitoral e a atuação dos mesmos após a eleição, entre outros, despertaram meu interesse em buscar os dados públicos dos candidatos (tse.gov.br) e traçar o perfil dos candidatos a prefeito em todo o país. </div></p>


## <div style="text-align: justify"> Objetivo</div> 
#### <p> <div style="text-align: justify"> Aplicar técnicas de mineração de dados e aprendizado de máquina para as campanhas eleitorais para prefeito no período entre 2010 e 2020, para:
  <ul>
  <li> identificar o perfil dos candidatos a prefeito em todas as regiões do país;
  <li> avaliar se há relação entre as características do perfil do candidato com a conquista do pleito;
  <li> analisar os perfis dos candidatos separados pelas Regiões Brasileiras; 
  <li> elaborar modelo preditivo com base no perfil do candidato, para indicar a “probabilidade” de  sucesso por Região do país.
  </ul>
  </div></p>
  
  
  ## <div style="text-align: justify"> Dados </div> 
 #### <p> <div style="text-align: justify"> A fonte primária dos dados é o [Repositório de dados Eleitorais do TSE](https://www.tse.jus.br/eleicoes/estatisticas/repositorio-de-dados-eleitorais-1).</div></p>
 ####  <p> <div style="text-align: justify">Os arquivos com os dados dos candidatos nos anos de 2012, 2016 e 2018 foram baixados do repositório do TSE, realizada a limpeza e integração dos datasets, deixando apenas os dados referentes aos candidatos a prefeito aptos. O arquivo base para as demais fases do trabalho é [base_20122020.xls](https://github.com/admaraia/PerfilCandPrefeito-Brasil/blob/main/base_20122020.xlsx) disponível neste repositório.</div></p>
 
   ## <div style="text-align: justify"> Métodos </div> 
 ####  <p> <div style="text-align: justify"> O tratamento e a normalização do dataset foi realizado no [tratamento_dados.ipynb] (https://github.com/admaraia/PerfilCandPrefeito-Brasil/blob/main/).</div></p>
 
 #### <p> <div style="text-align: justify"> Abaixo os tipos de dados que compõem o dataset após a primeira limpeza
 
<il>
 Tipos dos dados que compõem o dataset:
<li>ANO_ELEICAO   ------------------------->        Quantitativa discreto
<li>ABRANGENCIA   ------------------------>           Qualitativa nominal
<li>ESTADO       ------------------------------->            Qualitativa nominal
<li>MUNICIPIO     --------------------------->           Qualitativa nominal
<li>CARGO          -------------------------------->          Qualitativa nominal
<li>PARTIDO         ------------------------------>         Qualitativa nominal
<li>COLIGACAO           --------------------------->     Qualitativa nominal
<li>ESTADO_NASCIMENTO  --------------->      Qualitativa nominal
<li>MUNICIPIO_NASCIMENTO------------>    Qualitativa nominal
<li>DT_NASCIMENTO      --------------------->      Qualitativa ordinal
<li>GENERO           ------------------------------->        Qualitativa nominal
<li>GRAU_INSTRUCAO   -------------------->        Qualitativa ordinal
<li>ESTADO_CIVIL      ------------------------->       Qualitativa nominal
<li>COR_RACA          ---------------------------->       Qualitativa nominal
<li>SITUACAO_FINAL    --------------------->       Qualitativa nominal
<li>REELEICAO         ---------------------------->       Qualitativa nominal
<li>IDADE            --------------------------------->        Quantitativa discreto
<li>FAIXA_ETARIA_IBGE  ------------------->     Qualitativa ordinal
  </il></div></p>
