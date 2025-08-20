## Create a virtual enviroment for python:

python3 -m venv venv

## Activate the enviroment:

source ./venv/bin/activate (mac command)

## Install required dependencias:
pip install -r requirements.txt

## Pull ollama models:
ollama pull llama3.1:8b    
ollama pull mxbai-embed-large

## Vector Search:
It is a database; that is going to be hosted locally using ChromaDB.