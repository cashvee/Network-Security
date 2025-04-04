# Network Security ❗❗

This repository contains various resources and tools for network security analysis. The main focus is on using machine learning techniques to classify and detect network attacks.

## ⭐ Table of Contents
- [Overview](#overview)
- [Setup](#setup)
- [Usage](#usage)
- [Notebooks](#notebooks)
- [Datasets](#datasets)
- [Contributing](#contributing)

## 🛒Overview

The `Network-Security` repository includes Jupyter notebooks and scripts that demonstrate how to analyze network traffic data and classify different types of network attacks using machine learning algorithms. The repository leverages popular machine learning models to improve network security.

## 🐟Setup

To set up the project locally, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/cashvee/Network-Security.git
    cd Network-Security
    ```

2. Create a virtual environment and activate it:
    ```bash
    python3 -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

## 🍀Usage

To run the Jupyter notebooks, follow these steps:

1. Start the Jupyter notebook server:
    ```bash
    jupyter notebook
    ```

2. Open the `main_classification_kitsune.ipynb` notebook and execute the cells.

## Notebooks
### main_classification_kitsune.ipynb

🍓This notebook demonstrates how to classify network attacks using various machine learning algorithms. It includes the following steps:
- Loading libraries and data
- Initializing global functions and values
- Loading public datasets
- Displaying dataset contents
- Preprocessing data
- Training and evaluating machine learning models

🧷The notebook uses popular machine learning models such as:
- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- Gradient Boosting Classifier
- Support Vector Classifier (SVC)

## 🧶Datasets

The datasets used in this project are publicly available and can be loaded directly from the URLs provided in the notebooks. The datasets include various types of network attacks such as ARP MitM, Active Wiretap, Fuzzing, Mirai, OS Scan, SSDP Flood, SSL Renegotiation, SYN DoS, and Video Injection.

## 🧸Contributing
Contributions are more than welcome!
If you have any ideas, suggestions, or improvements, feel free to open an issue or submit a pull request.

