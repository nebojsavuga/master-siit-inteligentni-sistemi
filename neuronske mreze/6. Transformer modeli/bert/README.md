# Autoencoders

## Contents

* `requirements.txt` - dependencies
* `data/` - dataset
* Notebooks:
  - `BERT Embeddings.ipynb` - Binary text classificaiton on IMDb dataset
  - `Battle of BERTs.ipynb` - Fine-tuning multiple BERT models for multiclass text classification on Seriban language dataset

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
pip install numpy matplotlib jupyter transformers datasets torch tensroflow scikit-learn tf-keras accelerate
```

## Run

Starting the server via `jupyter notebook` or `jupyter-lab`.  
If using a virtual environment, it needs to be activated first. 
