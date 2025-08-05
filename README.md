# DBT Project for <nome do projeto>

Este projeto contém a modelagem de dados com DBT para os dados provenientes do Neon (PostgreSQL) e ingestão no Lakehouse (Databricks).

## Estrutura

- `models/staging`: modelos que representam os dados brutos
- `models/marts`: modelos de negócio (dimensões e fatos)
- `seeds`: dados fixos
- `snapshots`: controle de histórico
- `macros`: funções reutilizáveis

## Como rodar

```bash
dbt run
dbt test

