# Fraud-Detection-Algorithm

## Introduction
This project was focused on building a fraud detection dashboard  as a tool for fraud detection analysis, using python and streamlit app.  
It allows users to set a threshold for classifying transactions as fraudulent or normal. Additionally, it provides insights into the cost associated with different types of classification errors.

## Usage
1. **Threshold Setting**: Use the slider to adjust the threshold for classifying transactions. The default threshold is set at 50%.![Screenshot 2024-03-14 230323](https://github.com/gsr876/Fraud-Detection-Algorithm/assets/147017277/4d8adc2a-2e60-424f-a859-a495d8131564)

2. **Cost Input**: Input the costs associated with different classification outcomes: ![Screenshot 2024-03-14 230331](https://github.com/gsr876/Fraud-Detection-Algorithm/assets/147017277/45b1eef3-6585-4b06-b3df-5673f27a5a5e)

   - Cost of correctly detecting fraud (True Positive)
   - Cost of incorrectly classifying normal transactions as fraudulent (False Positive)
   - Cost of not detecting fraudulent transactions (False Negative)
   - Cost of correctly detecting normal transactions (True Negative)

## Metrics
The dashboard displays the following metrics:
- **Number of fraudulent transactions detected**: Transactions classified as fraudulent and were indeed fraudulent.
- **Number of fraudulent transactions not detected**: Transactions classified as normal but were actually fraudulent.
- **Number of good transactions classified as fraudulent**: Normal transactions misclassified as fraudulent.
- **Number of good transactions classified as good**: Transactions correctly classified as normal.
- **Total number of transactions assessed**: Sum of all transactions evaluated.

## Cost Analysis
The dashboard calculates and displays the total cost of fraud based on the provided costs and the classification outcomes. It shows both the default cost (before threshold adjustment) and the updated cost (after threshold adjustment).

## Important Note
Ensure that the threshold and cost inputs are carefully adjusted to reflect the specific context and priorities of the fraud detection task.

