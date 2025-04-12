# 🛒 Projeto de Vendas com PostgreSQL e Python

Este projeto tem como objetivo transformar dados de vendas em um banco de dados relacional PostgreSQL, aplicando consultas de análise com SQL puro.

---

## 🚀 Tecnologias usadas

- Python
- PostgreSQL
- Pandas
- Psycopg2
- IPython-SQL

---

## 📁 Estrutura

- Conexão com banco de dados
- Criação da tabela `vendas_final`
- Inserção dos dados a partir de um DataFrame (CSV)
- Consultas SQL com foco em insights de negócio

---

## 📊 Consultas realizadas

1. Quantidade de cada produto vendido por ano
2. Total de vendas por vendedor
3. Percentual do total de vendas por vendedor

---

## 🧱 Estrutura da Tabela `vendas_final`

| Campo           | Tipo     | Descrição                            |
|-----------------|----------|--------------------------------------|
| cod_produto     | texto    | Código identificador do produto      |
| nome_produto    | texto    | Nome do produto                      |
| categoria       | texto    | Categoria do produto                 |
| valor_venda     | numérico | Valor original da venda              |
| venda_final     | numérico | Valor com aumento aplicado           |
| nome_vendedor   | texto    | Nome do vendedor responsável         |
| data_venda      | date     | Data da venda                        |

---

## 📦 Execução

1. Clone o repositório
2. Instale os requisitos com `pip install -r requirements.txt`
3. Execute o notebook em `notebook/desafio_vendas_postgres.ipynb`

---

## 👤 Autor

Elvis Nascimento Bento  
https://www.linkedin.com/in/elvis-nascimento-dev/

