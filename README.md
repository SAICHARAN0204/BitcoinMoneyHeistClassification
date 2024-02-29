# Bitcoin Ransomware Classification Project

## Overview

This project focuses on classifying Bitcoin ransomware using machine learning classifiers, specifically Random Forest, K-Nearest Neighbors (KNN), and Support Vector Machine (SVM) algorithms.

## Table of Contents

- [Introduction](#introduction)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Results](#results)
## Introduction

Bitcoin is the world's largest cryptocurrency. Unlike fiat currency, Bitcoin is created, distributed, traded, and stored using a decentralized ledger system known as a blockchain.The Bitcoin Heist is a well-known case that has garnered the greatest media attention as a result of the increasing scandals. A substantial dataset that dates back to the Bitcoin Heist incident has been located. We will describe various approaches to determining whether or not transactions based on a given Bitcoin address are malicious using the foundations of  machine learning. We aims to elucidate the fundamentals of machine learning underlying ransomware and cryptocurrencies. We will achieve this by utilising multiple models, including SVM-RBF, K-Nearest Neighbour (KNN), and Random Forest.
![image](https://github.com/SAICHARAN0204/BitcoinMoneyHeistClassification/assets/82882226/d0b24789-9fed-4ebe-bdb6-fba3dd61f38c)

## Work Flow Diagram
![image](https://github.com/SAICHARAN0204/BitcoinMoneyHeistClassification/assets/82882226/966afc88-6b4e-4091-9a20-0d3d6aeb2cc7)



## Project Structure

- **`/data`**: Contains the dataset used for training and testing.
- **`/src`**: Source code for implementing Random Forest, KNN, and SVM classifiers.
- **`/results`**: Stores the results and evaluation metrics.
- **`/docs`**: Documentation for the project.

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/saicharan0204/bitcoin-ransomware-classification.git
    cd bitcoin-ransomware-classification
    ```

2. Install dependencies:

    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. Navigate to the `/src` directory:

    ```bash
    cd src
    ```

2. Run the scripts for each classifier:

    ```bash
    python random_forest_classifier.py
    python knn_classifier.py
    python svm_classifier.py
    ```

3. View the results in the `/results` directory.

## Results

| Classifier     | Accuracy | Precision | Recall | F1 Score |
|----------------|----------|-----------|--------|----------|
| Random Forest  | 0.9921   | 0.88      | 0.82   | 0.85     |
| KNN            | 0.9954   | 0.84      | 0.78   | 0.81     |
| SVM            | 0.96     | 0.90      | 0.86   | 0.88     |

