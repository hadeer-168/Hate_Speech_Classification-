# Hate Speech Classification

## Description
This project focuses on classifying tweets containing hate speech from other tweets. The task involves building a machine learning model to detect hate speech using a labeled dataset collected from Twitter.

## Dataset
- **Source:** Labeled dataset provided in the file `Lab 1 - Hate Speech.tsv`.
- **Labels:** 
  - `0` → No hate speech
  - `1` → Contains hate speech

## Objective
To accurately classify tweets based on the presence of hate speech, using the macro F1 score as the evaluation metric.

## Project Structure
1. **Data Loading:** Import the dataset from a TSV file.
2. **Data Splitting:** Separate the dataset into training and testing subsets before conducting Exploratory Data Analysis (EDA).
3. **Model Training:** Train a classification model using machine learning techniques.
4. **Evaluation:** Evaluate model performance using the macro F1 score.

## Installation
1. Clone this repository.
   ```bash
   git clone [repository_url]
   ```
2. Install the required Python libraries.
   ```bash
   pip install -r requirements.txt
   ```

## Usage
1. Load the dataset provided in `Lab 1 - Hate Speech.tsv`.
2. Run the Jupyter Notebook: `Lab 1 - Hate Speech Classification.ipynb`.
3. Follow the instructions in the notebook to preprocess data, train the model, and evaluate performance.
