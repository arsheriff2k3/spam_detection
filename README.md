## Email Classification using Logistic Regression

This project demonstrates how to classify emails as spam or ham (non-spam) using a Logistic Regression model. The code uses a dataset of labeled emails to train the model and then predicts the category of new emails based on their content.

### Dependencies
- NumPy
- pandas
- scikit-learn (sklearn)

### Setup
1. Place the 'mail_data.csv' file in the same directory as the code file.
2. Install the required dependencies using pip or any package manager:

pip install numpy pandas scikit-learn

vbnet


### Code Overview
The code performs the following steps:
1. Load the email data from a CSV file into a pandas DataFrame.
2. Preprocess the data by handling null values and converting labels to numerical values.
3. Split the data into training and testing sets.
4. Extract features from the text data using TF-IDF vectorization.
5. Train a Logistic Regression model on the training data.
6. Evaluate the model's accuracy on both the training and test data.
7. Demonstrate how to use the trained model to classify new email data.

### Example Usage
To classify a new email, modify the `input_mail` variable with the desired email text. Then run the code and observe the prediction.

### Notes
- The accuracy of the model on both the training and test data is displayed.
- The code assumes that the 'mail_data.csv' file contains the required columns: 'Category' and 'Message'.

For more details, refer to the source code or project repository.
