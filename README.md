# crawler-imoveis

MVP de crawler imobiliário com Python, DuckDB, CSV e Parquet.

## Estrutura inicial

- `data/ingestion`: dados brutos
- `data/bronze`: dados estruturados
- `data/silver`: dados normalizados
- `src/crawler_imoveis`: código-fonte

## Objetivo inicial

Coletar anúncios de imóveis em Ribeirão Preto, salvar em CSV/Parquet e evoluir para camadas bronze e silver.