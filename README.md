## 🏓 Smart Pong Analytics - Data Engineering Project
🇧🇷 Resumo do Projeto
Este projeto simula um ecossistema de dados para uma mesa de ping-pong inteligente. Ele abrange desde a ingestão de dados brutos (sensores/visão computacional), passando por limpeza e transformação (ETL), até a visualização em tempo real de métricas de performance e mapas de calor.

🇺🇸 Project Overview (English)
This repository features an end-to-end data engineering pipeline designed for sports analytics. It simulates real-time data ingestion from table tennis sensors, performing stream-like processing to calculate ball velocity and impact distribution. The project demonstrates core data engineering concepts: raw data handling (Bronze), data quality enforcement (Silver), and analytical visualization (Gold) using Python and Google Colab.

## 🚀 Tecnologias Utilizadas
* **Python 3.x**

* **Pandas (Processamento e Transformação)

* **Seaborn/Matplotlib (Visualização de Dados)

JSON/CSV (Armazenamento de arquivos)

📊 Funcionalidades
Data Ingestion: Simulação de sensores de alta frequência capturando posição (x, y) e velocidade.

Data Transformation: Conversão de unidades e enriquecimento de dados.

Data Quality: Filtros para remover leituras de sensores ruidosas ou impossíveis.

Streaming Simulation: Dashboard em tempo real que atualiza conforme as jogadas acontecem.

🗺️ Próximos Passos (Roadmap de Engenharia)
Para as próximas versões deste projeto, os objetivos de engenharia são:

📡 Ingestão Distribuída: Implementar o Apache Kafka para gerir múltiplos sensores de várias mesas em simultâneo.

⚡ Processamento em Batch Real: Migrar as transformações de Pandas para PySpark para suportar terabytes de dados históricos de torneios.

☁️ Cloud Data Lake: Configurar um pipeline automatizado para guardar os dados brutos no Amazon S3 e os dados processados no Google BigQuery.

🤖 Integração com ML: Criar um modelo de Machine Learning para prever a probabilidade de um ponto com base na trajetória da bola (Win Probability).

🛠️ Orquestração: Utilizar o Apache Airflow para agendar a limpeza de dados e a geração de relatórios diários para os treinadores.
