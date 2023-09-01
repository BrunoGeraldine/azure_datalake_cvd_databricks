# azure_datalake_cvd_databricks
Projeto de criação de um Data-Lake com arquitetura em camadas para ingestão, tratamento e visualização de dados.

Projeto estruturado utilizando Azure e databricks para ETL de dados e arquiteturação em camadas.


Fonte de dados: 
https://www.kaggle.com/datasets/cprete/covid19-open-datasets-for-brazil?resource=download



Descrição do Projeto:

Esse projeto é destinado para a criação de uma pipeline de dados capturando dados de um arquivo em formato ".csv" e alimentando um banco de dados em arquitetura de camadas para a disponibilização de dados brutos, tratados ou agregado optimizando a acessibilidade destes dados conforme a necessidade do time de negocios.

Utilizarei neste projeto a seguinte arquitetura:

Ingestão → armazenamento → camadas (layers) → data visualization / data valuation.

Camadas (layers)

Bronze → dados brutos (sem qualquer transformação) 

Silver → dados tratados (dados transformados e limpos - data scientist and data business)

Gold → dados transformados e agregados/modelados (data evaluation and data visualization - data analyst, dashboards, insights)





