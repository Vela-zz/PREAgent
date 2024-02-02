# Udaciyt LLM Final Object

## Environment 

1. install poetry first, or use conda with pip
```
pipx install poetry
poetry install 
#
conda env create -n udallm python=3.10
conda activate udallm
pip install -r requirements.txt
```

##

Check the notebooks under notebooke folder,

1. generate_data: real estate generation notebook, based on langchain.
2. create_embedding: vector database creation, langchain + lancedb
3. query_housematch: house match semantic search and llm rerank, langchain+lancedb
