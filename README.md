# Crop Recommendation System

This repository contains the code and resources for a crop recommendation system developed as part of a research project under the guidance of Dr. Bhuvaneswari Amma N.G. This project is published in IGI Global's "Machine Learning and Deep Learning for Smart Agriculture and Applications."

## Table of Contents

1. [Introduction](#introduction)
2. [Prerequisites](#prerequisites)
3. [Installation](#installation)
4. [Running the Project](#running-the-project)
5. [Usage](#usage)
6. [Screenshots](#screenshots)
7. [Research Publication](#research-publication)

## Introduction

This project provides a machine learning-based solution for recommending the type of crop to be grown based on various input parameters such as soil nutrients, temperature, humidity, pH, and rainfall.

## Prerequisites

Ensure you have the following software installed on your machine:

- Python
- Pip (Python package installer)
- Git

## Installation

1. **Clone the repository:**

    ```bash
    git clone https://github.com/yourusername/crop-recommendation-system.git
    cd crop-recommendation-system
    ```

2. **Download the dataset and the pre-trained model:**

    Ensure that `Crop_recommendation.csv` and `NB_model.pkl` are in the project directory.

## Running the Project

1. **Run the Flask application:**

    ```bash
    python app.py
    ```

2. **Access the web application:**

    Open your web browser and go to `http://127.0.0.1:5000/`.

## Usage

1. Enter the values for the following parameters in the web form:
    - N (Nitrogen content)
    - P (Phosphorus content)
    - K (Potassium content)
    - Temperature
    - Humidity
    - pH level
    - Rainfall

2. Click on the "Submit" button to get the recommended crop type.

## Screenshots

![image](https://github.com/Khushal-Kindra/Crop-Prediction/assets/159249366/c45de85b-e1b0-486d-bd01-276ec30c9b57)

## Research Publication

This project is part of a research manuscript titled "Machine Learning and Deep Learning for Smart Agriculture and Applications," published in IGI Global. The manuscript, `Manuscript_SubmittedCopy.docx`, is included in this repository.

## Files in the Repository

- `Crop_recommendation.csv`: The dataset used for training the model.
- `NB_model.pkl`: The pre-trained Naive Bayes model.
- `crop_prediction.ipynb`: Jupyter notebook containing the model training code.
- `index.html`: HTML template for the web interface.
- `app.py`: Flask application code.
- `Manuscript_SubmittedCopy.docx`: The research manuscript published in IGI Global.
