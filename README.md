# LLM Exploration and Learning Notebooks

My large language model (LLM) learning and exploration notebooks. 

## Setup

Sample `.envrc` shell environment:

```sh
layout python python3.11
use node 18

export PGHOST=localhost
export PGPORT=5432
export PGUSER=$USER
export PGDATABASE=llm_exploration
export DATABASE_URL=postgresql+psycopg://$PGUSER@$PGHOST:$PGPORT/$PGDATABASE

export OPENAI_API_KEY=fill-me-in
```

Install prerequisites:

```sh
brew install git-lfs
```

Install requirements:

```sh
pip install -r requirements.txt
pip install llm
llm install llm-gpt4all
```

Start JupyterLab:

```sh
jupyter-lab
```
