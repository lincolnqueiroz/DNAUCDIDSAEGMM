# DNAUCDIDSAEGMM: Detecting New Attacks under Concept Drift in Intrusion Detection Systems using Autoencoder Networks and Gaussian Mixture Models

This git repository provides code and instructions to reproduce results from this [paper](https://www.scitepress.org/Link.aspx?doi=10.5220/0014420800004052).

## Python Environment

Experiments were conducted using CUDA 12.4.

`python -m venv env`

` source env/bin/activate` for Linux or `./env/Scripts/activate` for Windows.

`pip install -r requirements.txt`

## Dataset

The full dataset used is the csv dataset and can be downloaded from https://www.unb.ca/cic/datasets/ids-2018.html

## Notebooks order

1. [Preprocessing](preprocessing.ipynb)
2. [Dataset Splitter](dataset_splitter.ipynb)
3. [1 Hidden Class Encoder Generator](1_class_hidden/encoder_generator.ipynb)
4. [1 Hidden Class GMM]()
5. [1 Hidden Class Threshold]()
6. [2 Hidden Classes Encoder Generator]()
7. [2 Hidden Classes GMM]()
8. [2 Hidden Classes Threshold]()
9. [Variation Hidden Class Encoder Generator]()
10. [Variation Hidden Class GMM]()
11. [Variation Hidden Class Threshold]()