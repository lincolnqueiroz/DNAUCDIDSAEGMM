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
4. [1 Hidden Class GMM](1_class_hidden/GMM.ipynb)
5. [1 Hidden Class Threshold](1_class_hidden/threshold.ipynb)
6. [2 Hidden Classes Encoder Generator](2_classes_hidden/encoder_generator.ipynb)
7. [2 Hidden Classes GMM](2_classes_hidden/GMM.ipynb)
8. [2 Hidden Classes Threshold](2_classes_hidden/threshold.ipynb)
9. Variation 
    1. DDoS attack-HOIC
        1. [Encoder Generator](variation/DDOS%20attack-HOIC/encoder_generator.ipynb)
        2. [GMM](variation/DDOS%20attack-HOIC/GMM.ipynb)
        3. [Threshold](variation/DDOS%20attack-HOIC/threshold.ipynb)
    2. DDoS attack-LOIC-UDP
        1. [Encoder Generator](variation/DDOS%20attack-LOIC-UDP/encoder_generator.ipynb)
        2. [GMM](variation/DDOS%20attack-LOIC-UDP/GMM.ipynb)
        3. [Threshold](variation/DDOS%20attack-LOIC-UDP/threshold.ipynb)
    3. DDoS attacks-LOIC-HTTP
        1. [Encoder Generator](variation/DDoS%20attacks-LOIC-HTTP/encoder_generator.ipynb)
        2. [GMM](variation/DDoS%20attacks-LOIC-HTTP/GMM.ipynb)
        3. [Threshold](variation/DDoS%20attacks-LOIC-HTTP/threshold.ipynb)
    4. DoS attack-Goldeneye
        1. [Encoder Generator](variation/DoS%20attacks-Goldeneye/encoder_generator.ipynb)
        2. [GMM](variation/DoS%20attacks-Goldeneye/GMM.ipynb)
        3. [Threshold](variation/DoS%20attacks-Goldeneye/threshold.ipynb)
    5. DoS attacks-Hulk
        1. [Encoder Generator](variation/DoS%20attacks-Hulk/encoder_generator.ipynb)
        2. [GMM](variation/DoS%20attacks-Hulk/GMM.ipynb)
        3. [Threshold](variation/DoS%20attacks-Hulk/threshold.ipynb)
    5. DoS attacks-Slowloris
        1. [Encoder Generator](variation/DoS%20attacks-Slowloris/encoder_generator.ipynb)
        2. [GMM](variation/DoS%20attacks-Slowloris/GMM.ipynb)
        3. [Threshold](variation/DoS%20attacks-Slowloris/threshold.ipynb)
    7. FTP-BruteForce
        1. [Encoder Generator](variation/FTP-BruteForce/encoder_generator.ipynb)
        2. [GMM](variation/FTP-BruteForce/GMM.ipynbb)
        3. [Threshold](variation/FTP-BruteForce/threshold.ipynb)
    8. SSH-Bruteforce
        1. [Encoder Generator](variation/SSH-Bruteforce/encoder_generator.ipynb)
        2. [GMM](variation/SSH-Bruteforce/GMM.ipynbb)
        3. [Threshold](variation/SSH-Bruteforce/threshold.ipynb)