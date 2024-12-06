# Prompt Engineering

## Contents

* `requirements.txt` - dependencies
* `template.jinja2` - Jinja template for generating prompt for `Prompting.ipynb`
* `data/` - dataset for `RAG.ipynb`
* Notebooks:
  - `Prompting.ipynb` - notebook with simple prompting techniques
  - `RAG.ipynb` - notebook with RAG applied on PDFs in Serbian language.

## Setup

1. Install `Python 3.10.` or newer (tested with `Python 3.10.13`)
2. Install dependencies:
   * Directly:
     * `pip install -r requirements.txt`
   * In virtual environment:
     * Create virtual environment: `python -m venv env`  
     * Activate the virtual environment: `virtualenv env`  
     * Install dependencies: `pip install -r requirements.txt`

If there are errors while installing requirements, dependencies can be alternatively installed via:  
```
pip install jupyter langchain langchain_community pypdf langchain_chroma langchain_openai
```

## Run

Starting the server via `jupyter notebook` or `jupyter-lab`.  
If using a virtual environment, it needs to be activated first. 
