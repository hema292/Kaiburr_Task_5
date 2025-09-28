# Consumer Complaint Classification

This project classifies consumer complaints into four categories:  
**Credit Reporting, Debt Collection, Consumer Loan, and Mortgage**.  

It uses **TF-IDF vectorization** and multiple machine learning models (Logistic Regression, Naive Bayes, Linear SVM) to predict the category of a complaint from its text.

---

## Features

- Filters complaints to 4 key categories  
- Cleans and preprocesses text (lowercasing, punctuation removal, stopword removal)  
- Converts text into TF-IDF vectors  
- Trains and evaluates multiple models  
- Provides classification report and accuracy/F1 metrics  
- Predicts category for new complaint text  

---

## Installation

1. Clone this repository:

```bash
git clone https://github.com/hema292/consumer-complaint-classifier.git
cd consumer-complaint-classifier

Load your CSV dataset (ensure the path is correct in DATA_FILE)

Run the script to:

Filter target categories

Clean and preprocess complaint text

Train models (Logistic Regression, Naive Bayes, Linear SVM)

Evaluate models with accuracy, F1 score, and classification report

Plot complaint distribution by product

Example Output

Predicted Category: Mortgage

Confusion matrices and classification reports for all models are displayed after training.

License

This project is open-source and available under the MIT License.
