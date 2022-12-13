# Credit Score

## Credit Scoring for Utiva 

Credit scoring is a statistical analysis performed by lenders and financial institutions to determine the creditworthiness of a person or a small, owner-operated business. Credit scoring is used by lenders to help decide whether to extend or deny credit. A credit score can impact many financial transactions, including mortgages, auto loans, credit cards, and private loans.

Link to the Kaggle Dataset: https://www.kaggle.com/competitions/credit-scoring-utiva-challenge/

## How is the creditworthiness of a client determined?
### Summary
- Used 20 __feature__ columns and 1 __target__ column
- 13 Categorical and 7 Continuous columns
- Split data into training and validation sets using sklearn’s __train_test_split__ function.
- It took less than __a minute__ to train the model.

### Feature Transformation
- Used the __proc_data__ function to convert columns to Categorical features, and to fill NaN with modal data
- The __convert_str_years__ function is used to convert date data from string to integer values.

### Training
Obtained a mean absolute error of 0.2429

### Conclusion
- Simple models like the Random Forest Classifier can solve problems related to Credit Scoring. Complex does not mean better.
- The mean absolute error is __0.2429__. There is still room for improving the model.
- Random Forests are not complicated at all, they can be used to implement the solution to problems like Credit Scoring as quickly as possible.
- Also, they are not sensitive to issues like Normalization or Non-linear transformations, making them easy to work with.


# By Ubajaka, Chijioke

## Prerequisites:
- Google Colab | IPython Notebook
- Sklearn
- Google Drive (Optional)
