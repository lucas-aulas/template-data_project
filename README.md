<div align="center">
    <img src="https://picsum.photos/seed/picsum/1080/200">
	<hr>
<h1>PROJECT: for ...</h1>

<img src="https://img.shields.io/badge/License-MIT-750014.svg">
<img src="https://img.shields.io/pypi/pyversions/quati?logo=python&logoColor=white&label=Python">
<br>
<img src="https://img.shields.io/badge/Code Style-Black Formatter-111.svg"> 
<br>

</div>

## What is it?
Description paragraph

<h2>Table of Contents</h2>

- [What is it?](#what-is-it)
- [Main Features](#main-features)
- [Where to get it / Install](#where-to-get-it--install)
- [Documentation](#documentation)
- [License](#license)
- [Dependencies](#dependencies)
- [Project Structure](#project-structure)

## Main Features

⠀⠀[**`some_function()`**](_____): quick description <br>
⠀⠀[**`some_feature`**](_____): quick description <br>
⠀⠀[**`SomeClass`**](_____): quick description <br>
⠀⠀...

## Where to get it / Install
The source code is currently hosted on GitHub at: https://github.com/_____

> [!WARNING]
> It's essential to use [**Python 3.10**](https://www.python.org/downloads/release/python-310/) version

- GitHub
	```sh
	# GitHub
	pip install git+https://github.com/_____
	```

- Setup
	```sh
    # Linux
	python3.10 -m venv .venv  # cria ambiente virtual
	source .venv/bin/activete # ativa o ambiente virtual
	python script.py          # executa o script
	```
	```sh
    # macOS
    ...
	```
	```sh
    # Windows
    ...
	```

## Documentation
- [Documentation](https://github.com/_____/_____/blob/main/docs/_____.md)

## License
- [_____](https://github.com/_____/blob/main/LICENSE)

## Dependencies
- [_____](https://pypi.org/project/_____)

## Project Structure

```sh
•
├── README.md # Visão geral e instruções do projeto
├── requirements.txt # Dependências Python
│
├── artifacts # Modelos .pkl, embeddings e objetos serializados
│   └── revenue_model.pkl
│
├── bin # Binários e executáveis auxiliares
│   └── chromedriver.exe
│
├── dashboard # Dashboards e arquivos visuais
│   └── marvel_vs_dc.pbix
│
├── data # Camadas do Data Lake
│   ├── bronze # Dados brutos ingeridos
│   │   └── bronze_imdb_movies_raw.csv
│   │
│   ├── gold # Camada analítica/modelagem dimensional
│   │   └── fact_movie_performance.parquet
│   │
│   ├── raw # Dados originais das fontes externas
│   │   └── imdb_movies.csv
│   │
│   └── silver # Dados tratados e enriquecidos
│       └── silver_movies.parquet
│
├── docs # Documentação técnica
│   └── architecture.md
│
├── logs # Logs de execução e erros
│   └── pipeline.log
│
├── notebooks # Exploração e validação analítica
│   └── exploration.ipynb
│
├── pipelines # Pipelines ETL principais
│   ├── gold # Construção da camada Gold
│   │   └── build_fact_table.py
│   │
│   ├── ingestion # Ingestão de dados
│   │   └── ingest_imdb.py
│   │
│   └── transformation # Transformação e limpeza
│       └── transform_movies.py
│
├── secrets # Credenciais e arquivos sensíveis
│   └── service_account.json
│
├── sql # Scripts SQL analíticos e estruturais
│   └── analytics_queries.sql
│
├── src # Código-fonte principal da aplicação
│   ├── database # Persistência e conexão com banco
│   │   └── postgres_connection.py
│   │
│   ├── gold # Regras da camada Gold
│   │   └── build_dimensions.py
│   │
│   ├── ingestion # Funções auxiliares de ingestão
│   │   └── imdb_loader.py
│   │
│   ├── transform # Funções de transformação
│   │   └── financial_metrics.py
│   │
│   └── utils # Funções utilitárias reutilizáveis
│       └── parsing.py
│
├── tests # Testes automatizados
│   └── test_metrics.py
│
├── tmp # Arquivos temporários
│   ├── cache # Cache intermediário
│   │   └── cached_movies.pkl
│   │
│   ├── checkpoints # Controle de execução
│   │   └── pipeline_checkpoint.json
│   │
│   └── exports # Exportações temporárias
│       └── movies_export.csv
│
└── utils # Helpers e scripts utilitários independentes
    └── file_utils.py
```

<hr>

[⇧ Go to Top](#table-of-contents)