![Diagrama sem nome drawio](https://github.com/user-attachments/assets/49464352-58bc-4363-a8c7-5bce38a81159)

- **RabbitMQ** → Fila de dados para comunicação assíncrona.  
- **Python** → Processamento dos dados recebidos do RabbitMQ.  
- **Data Lake (Parquet)** → Armazena os dados brutos em um formato eficiente.  
- **Supabase** → Banco de dados intermediário para armazenamento temporário.  
- **ETL** → Processo de extração, transformação e carga dos dados.  
- **ClickHouse** → Banco de dados analítico otimizado para consultas rápidas.  
- **Visualização (Grafana)** → Dashboards para análise e visualização dos dados.  
---------------------------------------------------------------------------------------------------------------------------- 
- O **RabbitMQ** permite **alta escalabilidade e processamento assíncrono**.  
- O **Parquet** no **Data Lake** reduz o espaço de armazenamento e melhora a leitura.  
- O **Supabase** facilita a manipulação temporária dos dados.  
- O **ClickHouse** é altamente eficiente para **análises em tempo real**.   
---------------------------------------------------------------------------------------------------------------------------  
| **Componente**      | **Descrição** |
|---------------------|--------------|
| **RabbitMQ**       | Mensageria para ingestão assíncrona de dados. |
| **Python**         | Processa os dados e os envia ao Data Lake. |
| **Data Lake (Parquet)** | Armazena dados brutos no formato Parquet. |
| **Supabase**       | Banco intermediário para dados estruturados. |
| **ETL**            | Extrai, transforma e carrega os dados para o ClickHouse. |
| **ClickHouse**     | Banco de dados analítico para consulta otimizada. |
| **Visualização**   | Dashboard para análise e exibição dos dados. |
-----------------------------------------------------------------------------------------------------------------------------
- O uso do **Parquet** para otimizar armazenamento.  
- A necessidade de um **banco intermediário (Supabase)** antes da ETL.  
- A escolha do **ClickHouse** para análises rápidas.

Fontes usadas:
- https://app.diagrams.net/
- https://chatgpt.com/
- https://adalove.inteli.edu.br/
- Documentação disponibilizada pelo professor e desenho feito na lousa
