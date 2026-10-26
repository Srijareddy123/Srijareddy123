# Srija Gudi

I'm an AI engineer with 3+ years of work on retrieval-augmented generation, document extraction, LLM fine-tuning, and ML and data pipelines. These repos are personal projects built on public data, and each one runs on small demo data with one command.

[LinkedIn](https://www.linkedin.com/in/srija-gudi/)

## AI Engineering

- [filing-citations](https://github.com/Srijareddy123/filing-citations): question answering over SEC filings that quotes the filing, section and page or refuses; 128-question golden set, with a local 1.5B model, citation precision reached 0.63 and refusal accuracy 0.66 (in different configurations).
- [rag-document-pipeline](https://github.com/Srijareddy123/rag-document-pipeline): RAG ingestion with document quality checks; load tested on 49,499 Wikipedia articles (125,136 chunks in 11.6 minutes, 11.9 ms median query).

## ML and Data Science

- [ml-inference-pipeline](https://github.com/Srijareddy123/ml-inference-pipeline): XGBoost failure classifier with an MLflow registry and drift alerts; precision 0.93 and recall 0.79 on a held-out split of the AI4I 2020 data.
- [filing-extractor](https://github.com/Srijareddy123/filing-extractor): loan terms from SEC 8-K exhibits into a typed schema; 480 labeled passages and a rules baseline at 0.71 answer F1, with the LoRA fine-tune pending a GPU run.

## Data Engineering

- [fleet-telematics-etl](https://github.com/Srijareddy123/fleet-telematics-etl): Airflow, MinIO and PostgreSQL ETL for vehicle telematics; upserts 100,000 rows in about 7 seconds.
- [data-quality-framework](https://github.com/Srijareddy123/data-quality-framework): per-load checks for nulls, schema and drift; catches every schema change type in testing, with 0.4% of clean loads flagged.
- [edgar-stream](https://github.com/Srijareddy123/edgar-stream): streaming SEC filings into a DuckDB star schema; 638 ms median and 1.8 s p95 from event to queryable on a replay of 5 real days.
