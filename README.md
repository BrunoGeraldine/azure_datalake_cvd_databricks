# azure_datalake_cvd_databricks


<p align="center">
  <img width="500" height="200" src="https://github.com/BrunoGeraldine/azure_datalake_cvd_databricks/assets/87772120/fda00310-963e-4d3c-985e-29aa4698a7c7"
       </p>

**Bem-vindo ao Projeto de Criação de Data-Lake com Arquitetura em Camadas para Ingestão, Tratamento e Visualização de Dados utilizando Azure e Databricks**

---

### Descrição do Projeto

Este projeto tem como objetivo criar uma pipeline de dados robusta, implementando uma arquitetura em camadas para a ingestão, tratamento e visualização eficiente de dados. Utilizando Azure e Databricks, a pipeline captura dados de um arquivo CSV, os processa em camadas distintas (Bronze, Silver e Gold) e os disponibiliza para atender às diferentes necessidades dos diferentes times dentro da organização.

---

### Arquitetura

1. **Ingestão:**
   - Captura de arquivo em formato .CSV

2. **Armazenamento e Orquestração:**
   - Utilização do Azure Databricks para armazenamento e orquestração eficiente do pipeline.

3. **Tratamento:**
   - Processamento de dados utilizando PysPark no ambiente Databricks.

4. **Camadas (Layers):**
   - **Bronze:** Dados brutos, sem qualquer transformação.
   - **Silver:** Dados tratados, transformados e limpos, destinados a cientistas de dados e profissionais de negócios.
   - **Gold:** Dados transformados, agregados e modelados para avaliação e visualização, atendendo a analistas de dados, dashboards e insights.

---

### Fonte de Dados

Os dados utilizados neste projeto foram obtidos do Kaggle, disponíveis em [Covid-19 Open Datasets for Brazil](https://www.kaggle.com/datasets/cprete/covid19-open-datasets-for-brazil?resource=download).

---

### Tecnologias Aplicadas

- **Azure Databricks:** Para armazenamento, orquestração e processamento eficiente.
- **PysPark:** Utilizado para o tratamento avançado de dados no ambiente Databricks.
- **Camadas (Layers):** Estrutura Bronze-Silver-Gold para atender diferentes necessidades de usuários.

---

### Como Utilizar

1. **Configuração do Ambiente:**
   - Configurar as credenciais do Azure Databricks.
   - Certificar-se de que o ambiente esteja configurado conforme as especificações do projeto.

2. **Ingestão e Processamento:**
   - Executar o notebook Databricks na ordem especificada para realizar a ingestão, tratamento e armazenamento em camadas.

3. **Visualização de Dados:**
   - Utilizar as ferramentas de visualização integradas para explorar e avaliar os dados em diferentes camadas a sua escolha.

---

### Contribuições

Contribuições são encorajadas! Sinta-se à vontade para abrir issues, propor melhorias ou enviar pull requests para aprimorar a eficiência e funcionalidades da pipeline.

---

### Licença

Este projeto está licenciado sob a [Licença MIT](LICENSE).

---

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
