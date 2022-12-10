# Datalake / ETL e ELT

## Lake vs Warehouse

Lake: 
- Não estruturado
- Raw
- Grande
- Mais barato

Warehouse:
- Menores
- Batch Processing
- Relacional

## ETL vs ELT
ETL:
- Quantidade menor de dados
- Datawarehouse

ELT:
- Maior quantidade de dados
- Datalake
  
### Datalake storage
GCP -> Cloud storage
AWS -> S3
Azure -> Azure Blob


# Orquestração
Separar as depedências do pipeline
![airlfow](https://github.com/DataTalksClub/data-engineering-zoomcamp/raw/main/week_2_data_ingestion/airflow/docs/arch-diag-airflow.png?raw=true)



![overview-image-flow-chart](https://github.com/matheusbuniotto/Eng-Dados-Projeto/blob/master/assets/jobs_orchestration.drawio.png?raw=true)

