# Email-filtering
Spam/ham Email Classifier AI model 

# README

## Spam Detection using Logistic Regression

This project aims to build a spam detection model to classify messages as either 'spam' or 'ham' (non-spam) using logistic regression.

### Prerequisites

Ensure you have the following libraries installed: `numpy`, `pandas`, `scikit-learn`.

### Dataset

The dataset (`mail_data.csv`) contains messages labeled as 'spam' or 'ham' with two columns: `Category` and `Message`.

### Steps

1. **Load and Inspect Data**: Load the dataset and check its structure.

2. **Data Cleaning**: Replace missing values with empty strings.

3. **Encode Labels**: Convert 'spam' to 0 and 'ham' to 1.

4. **Split Data**: Separate the data into features (`X`) and labels (`Y`), then split into training and test sets.

5. **Feature Extraction**: Transform text data into TF-IDF features using `TfidfVectorizer`.

6. **Train the Model**: Train a logistic regression model using the training data.

7. **Evaluate the Model**: Calculate accuracy on both training and test data to evaluate model performance.

### Results

- **Accuracy on Training Data**: 96.62%
- **Accuracy on Test Data**: 96.47%

### Conclusion

The logistic regression model achieves high accuracy in classifying messages as spam or ham. Further improvements can be explored through different preprocessing techniques, feature extraction methods, and model tuning.

### Files

- `mail_data.csv`: Dataset file.
- `spam_detection.py`: Python script for training and evaluating the model.

