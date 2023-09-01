# azure_datalake_cvd_databricks


<p align="center">
  <img width="800" height="300" src="https://github.com/BrunoGeraldine/azure_datalake_cvd_databricks/assets/87772120/fda00310-963e-4d3c-985e-29aa4698a7c7"
       </p>

Projeto de criação de um Data-Lake com arquitetura em camadas para ingestão, tratamento e visualização de dados, utilizando Azure e databricks para orquestração e ETL de dados.

Esse projeto é destinado apenas para a criação de uma pipeline de dados capturando dados de um arquivo em formato ".csv" e alimentando um banco de dados em arquitetura de camadas para a disponibilização de dados brutos, tratados ou agregado optimizando a acessibilidade destes dados conforme a necessidade do time de negocios.

Utilizei neste projeto a seguinte arquitetura:

Ingestão → armazenamento → tratamento → armazenamento/camadas (layers) → data visualization/data valuation.

### Ingestão:
Captura de arquivo .csv

### Armazenamento e Orquestração

Azure DataBricks

### Tratamento → PysPark Databricks

Camadas (layers)

Bronze → dados brutos (sem qualquer transformação) 

Silver → dados tratados (dados transformados e limpos - data scientist and data business)

Gold → dados transformados e agregados/modelados (data evaluation and data visualization - data analyst, dashboards, insights)



Fonte de dados: 
https://www.kaggle.com/datasets/cprete/covid19-open-datasets-for-brazil?resource=download

