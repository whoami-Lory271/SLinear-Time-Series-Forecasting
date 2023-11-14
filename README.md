# SLinear: Taming the Non-Stationarity in Long Sequence Time Series Forecasting

This repository contains the complete implementation and procedure for training and evaluating the benchmark models. I have removed all
personal Google Drive folder and the wanDB page; if you want to test the code yourself, you will need the datasets and a
wanDB account. The comment in the code highlights the part to be filled in.

In any case, you need to keep the following folder structure:

```
.
├── best_predictions
├── checkpoints
├── datasets
├── encoding
├── forecasting_result
├── logs
├── models
├── test
└── tools

```

## Repository structure

The repository contains several Google Colab notebooks, all of which can be used to train, test and evaluate all of our models.
The following projects are in Pytorch Lightning: LSTM_Linear_pipeline, CoST_pipeline

### LSTM_Linear_pipeline.ipynb

Contains the implementation of our new models (SLinear and DaLinear) and the LSTF-Linear baseline, such as Linear and NLinear. 

### CoST_pipeline.ipynb

In this notebook we can find all the CoST variants, in particular CoSPy, CoST+Linear and CoST+NLinear.

### CoST_Pyraformer.ipynb

With this notebook you can run the official implementation of Pyraformer

### NLinear_train.ipynb

With this notebook you can run the official implementation of LSTF-Linear

### CoST_train.ipynb

Use this notebook to run the official implementation of CoST

## Reproducibility

As it is, the notebook does **not** work.
In order to test yourslef the models provided, you need to complete the section marked in the follwoing way:

```
### TODO ###
.

.
.
.
############

```
The other hyperparameters can be modify at will.

## Useful Link
[Datasets](https://drive.google.com/drive/folders/1TEf4A4uA_YzQ1G3S3M34sfeixKQN2Jm2?usp=sharing)  
[Thesis](MS_THESIS_LORENZO_DE_SANTIS_1849114.pdf)

## Citation

Please consider citing this work if you find it useful for your research.

```
@masterthesis{slinear,
    title        = {SLinear: Taming the Non-Stationarity in Long Sequence Time Series Forecasting},
    author       = {Lorenzo De Santis},
    year         = 2023,
    school       = {Sapienza, University of Rome},
    type         = {Master's thesis}
}

```
