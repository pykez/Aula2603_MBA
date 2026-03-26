# Data Integration e Pipelines — Aula 4

Disciplina do MBA em Data Engineering da FIAP.
Professor: Rafael S Novo Pereira

## Sobre esta aula

Última aula da disciplina. O tema é orquestração de pipelines com Apache Airflow.
Os alunos constroem um pipeline que baixa dados do GitHub, carrega no Snowflake,
transforma em camadas Bronze/Silver/Gold, roda validações de qualidade e envia
notificação por email. Tudo orquestrado por uma DAG no Airflow rodando no Astro
(plataforma managed da Astronomer).

O dataset usado é o Brazilian E-Commerce Public Dataset da Olist, disponível
no Kaggle sob licença CC BY-NC-SA 4.0.

## Contexto no currículo

Esta é a quarta e última aula de uma disciplina de 16 horas:

- Aula 1 — Databricks: pipeline Bronze/Silver/Gold com PySpark
- Aula 2 — Snowflake: pipeline com SQL, Tasks, Streams e Azure Blob
- Aula 3 — dbt Cloud: transformações testáveis e qualidade de dados
- Aula 4 — Airflow: orquestração de ponta a ponta (este repositório)

## Ferramentas utilizadas

- Apache Airflow 3.1 (via Astronomer Astro — trial gratuito de 14 dias)
- Snowflake (trial de 30 dias — conta individual de cada aluno)
- Python 3.10+ com pandas e snowflake-connector-python
- GitHub como fonte de dados para o pipeline



