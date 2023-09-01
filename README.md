# azure_datalake_cvd_databricks


<p align="center">
  <img width="500" height="200" src="https://github.com/BrunoGeraldine/azure_datalake_cvd_databricks/assets/87772120/fda00310-963e-4d3c-985e-29aa4698a7c7"
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



### Fonte de dados: 
https://www.kaggle.com/datasets/cprete/covid19-open-datasets-for-brazil?resource=download

### Técnologias aplicadas:
 <p align="left">
  <img width="100" height="30" src="https://github.com/BrunoGeraldine/azure_datalake_cvd_databricks/assets/87772120/b5964c2b-778b-4cd1-90b5-bbdf2a934c6d"
    </p>
  <img width="100" height="30" src="https://github.com/BrunoGeraldine/azure_datalake_cvd_databricks/assets/87772120/66e16d39-2405-4400-9cb0-564f647afaa1"
    </p>
  <img width="110" height="40" src="https://github.com/BrunoGeraldine/azure_datalake_cvd_databricks/assets/87772120/35957f03-034f-45ea-bd0b-d725f6849e86"
   </p>
 
<p align="left">
  <img width="110" height="30" src="https://github.com/BrunoGeraldine/azure_datalake_cvd_databricks/assets/87772120/d0735520-8c24-4212-ab45-ff8e539b4f7d"
       </p>  
  <img width="110" height="50" src="https://github.com/BrunoGeraldine/azure_datalake_cvd_databricks/assets/87772120/67a7109f-f589-4993-bc0f-06150fe91463"
       </p>

### Linguagens utilizadas:
<p align="left">
  <img width="120" height="50" src="https://github.com/BrunoGeraldine/azure_datalake_cvd_databricks/assets/87772120/53a34a21-e8dc-4ee9-978a-6590e75d54fd"
       </p> 
  <img width="120" height="50" src="https://github.com/BrunoGeraldine/azure_datalake_cvd_databricks/assets/87772120/a5e7a834-2c61-4b08-adb1-7524fb9b210c"
       </p> 
