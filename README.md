# Market Sentiment Classification of Financial Tweets

Sentiment classification of financial tweets, comparing 13 models in 29 configurations, from classical baselines to decoder-only transformers, with an agentic orchestrator and a RAG-based verification workflow. Best validation F1: **0.853**.

Course project for Text Mining, MSc in Data Science and Advanced Analytics, NOVA IMS (2026).

## What the project does

- Classifies the market sentiment of short financial texts (tweets).
- Compares 13 models across 29 configurations to find the best trade-off between accuracy and cost.
- Includes four decoder classifiers: GPT-2, Phi-3-mini, Phi-4-mini-instruct and Gemma-4-E4B.
- Adds an agentic orchestrator and a RAG-based agentic verification step that re-checks uncertain predictions.

## Repository contents

| File | Description |
| --- | --- |
| `report_12.pdf` | Project report: data, methods, experiments and results |
| `tm_final_12.ipynb` | Final notebook |
| `tm_tests_12.ipynb.txt` | Experiments and model tests (rename to `.ipynb` to open in Jupyter) |
| `pred_12.csv` | Predictions on the test set |

## Tech stack

Python · Hugging Face Transformers · LLMs · RAG · agentic workflows

## Authors

Team: Joao Cardoso, Simon Sazonov, Artem Polikarpov · [LinkedIn](https://www.linkedin.com/in/artem-polikarpov-068a4313) · [All projects](https://github.com/apnovaims)
