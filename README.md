## Relation Extraction from Natural Language using PyTorch


## Introduction

in this homework, we will implement a relation extraction model using PyTorch. The model is based on the


## Requirements

The project uses [Python 3.10](https://www.python.org/downloads) which has some linting defaults which may cause import
errors if using python < 3.10 and [PyTorch](https://pytorch.org/)

The requirements can be installed using the following command:

```bash
    pip install -r requirements.txt
```

## Running the code

The code has been written in jupyter notebook so that each part can be run individually and test different senarios and variables along the way. The notebook can also be imported into colab as well if you prefer working in the cloud GPU.



## Project Structure

The project is structured as follows:

```bash
    .
    ├── data
    │   ├── hw1_test-2.csv
    │   ├── hw1_train-2.csv
    │   └── sampleSubmission-2.csv
    ├── output
    │   ├── best_model.pt
    │   └── submission_labels.csv
    ├── README.md
    ├── requirements.txt
    └── notebook.ipynb
```

The `data` folder contains the data files for the project. The `notebook` is a jupyter notebook which contains the code
for the project. 


## Model

For this task, I've used different models with different structres, including bi-LSTM, MLP, with different number of hidden layers and methods like dropout, different learning rate, and using leaky relu activation. 



## Authors

Parsa Mazaheri, November 2022