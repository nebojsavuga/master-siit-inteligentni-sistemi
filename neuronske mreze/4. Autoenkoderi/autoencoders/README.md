# Autoencoders

## Contents

* `requirements.txt` - dependencies
* `data/` - dataset
* `images/` - images for the notebooks
* `weights/` - weights for the best model for fine-tuned VGG16 model
* Notebooks:
  - `Simple Autoencoder.ipynb` - Simple autoencoder on MNIST dataset
  - `Convolutional Autoencoder.ipynb` - Convolutional autoencoder for denoising MNIST dataset images
  - `VGG16 Fine tuning.ipynb` - Fine-tuning VGG16 model on CIFAR10 dataset
  - `Word2Vec.ipynb` - Training custom CBoW using Keras
  - `RNN Binary Classification.ipynb` - Binary text classification on IMDb dataset

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
pip install tensorflow matplotlib jupyter scipy gensim
```

## Run

Starting the server via `jupyter notebook` or `jupyter-lab`.  
If using a virtual environment, it needs to be activated first. 
