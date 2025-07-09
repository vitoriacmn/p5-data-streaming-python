# Simulação de Streaming de Dados com PySpark no Google Colab

Este projeto tem como objetivo demonstrar, de forma prática, o funcionamento de uma arquitetura de streaming de dados utilizando o Apache PySpark no ambiente do Google Colab.

## Resumo

A simulação é realizada por meio da leitura contínua de arquivos CSV inseridos em um diretório monitorado. O notebook exemplifica conceitos fundamentais de processamento de dados em tempo real com Spark Structured Streaming, utilizando um esquema de dados simples com colunas de nome, idade e cidade.

## Metodologia

- Instalação e configuração do PySpark no Google Colab.
- Criação de um schema fixo para os dados.
- Inicialização de uma `SparkSession`.
- Leitura de arquivos em modo `streaming` a partir de um diretório local (`/content/dados`).
- Simulação da chegada de dados via inserção manual de arquivos CSV.

## Tecnologias utilizadas

- Python
- Apache PySpark
- Google Colab
