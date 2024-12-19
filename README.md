# sms_spam_detector

# SMS Text Classification with Gradio Interface

This project implements a machine learning pipeline to classify SMS messages as spam or ham (not spam) using Python. It leverages Scikit-learn for the machine learning pipeline and Gradio for creating an interactive user interface.

## Features

- **TF-IDF Vectorization**: Converts text data into numerical features.
- **Linear Support Vector Classification (LinearSVC)**: Classifies messages based on extracted features.
- **Gradio Integration**: Provides a user-friendly web-based interface to test the model in real time.

## Requirements

- Python 3.7+
- Libraries:
  - `pandas`
  - `scikit-learn`
  - `gradio`

1. **Data Preparation**:
   - The dataset contain two columns:
     - `text_message`: The SMS text.
     - `label`: The classification label (e.g., "spam" or "ham").

2. **Model Training**:
   - The text data is vectorized using TF-IDF.
   - A Linear Support Vector Classifier is trained on the labeled data.

3. **Interactive Interface**:
   - Gradio is used to create a web-based interface where users can input SMS messages to get predictions.

## Usage

2. **Use the Interface**:
   Once the interface is launched, enter an SMS message in the input field and get an instant classification result.

## File Structure

- **Code**:
  - Data loading, preprocessing, model training, and Gradio interface setup are all encapsulated in the notebook.
- **Functions**:
  - `sms_classification(sms_text_df)`: Handles model training and evaluation.

