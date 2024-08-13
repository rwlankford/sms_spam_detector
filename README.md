# SMS Spam Detector Project
Module 21 Challenge

## Overview

This project consists of two Jupyter notebooks that demonstrate the process of building and deploying an SMS text classification model. The model is designed to classify SMS messages as either "spam" or "ham" (not spam). Below is a brief description of each notebook.

## Notebooks

### 1. `sms_text_classification_solution.ipynb`

This notebook covers the end-to-end process of building an SMS text classification model. It includes the following sections:

- **Data Preprocessing:** The raw SMS text data is loaded and preprocessed, including text cleaning, tokenization, and converting text to numerical features.
- **Model Training:** Several machine learning models are trained and evaluated, including a logistic regression model, a Naive Bayes classifier, and others.
- **Model Evaluation:** The models are evaluated using accuracy, precision, recall, and F1 score to determine the best-performing model.
- **Conclusion:** The best model is selected and saved for further use.

### 2. `gradio_sms_text_classification.ipynb`

This notebook demonstrates how to deploy the SMS text classification model using Gradio, an open-source Python library that allows you to quickly create customizable user interfaces for machine learning models. The notebook includes the following sections:

- **Loading the Trained Model:** The best model from the previous notebook is loaded.
- **Gradio Interface:** A user interface is created using Gradio to allow users to input SMS text and receive a classification (spam or ham) in real-time.
- **Running the Interface:** The Gradio interface is launched, enabling users to interact with the model.

## How to Use

1. **Clone the Repository:** Clone this repository to your local machine.
2. **Install Dependencies:** Install the required Python packages using `pip install -r requirements.txt`.
3. **Run Notebooks:**
   - Open `sms_text_classification_solution.ipynb` in Jupyter Notebook or Jupyter Lab to train the SMS classification model.
   - Open `gradio_sms_text_classification.ipynb` to launch the Gradio interface and interact with the trained model.
4. **Deploy the Gradio Interface:** Follow the instructions in the `gradio_sms_text_classification.ipynb` notebook to deploy the interface locally or on a server.

## Requirements

- Python 3.x
- Jupyter Notebook or Jupyter Lab
- Required Python packages (see `requirements.txt`)

## Conclusion

These notebooks provide a comprehensive guide to building, evaluating, and deploying an SMS text classification model. The use of Gradio for deployment makes it easy to create an interactive interface for the model.


