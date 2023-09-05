# Email Spam Detection with Machine Learning

This is a simple web application that utilizes machine learning to classify emails into two categories:

- Spam: Unwanted and unsolicited emails sent in bulk.
- Ham: Legitimate and desired emails that users expect.

## Getting Started

To run this application locally, follow these steps:

1. Clone this repository:

   ```bash
   git clone https://github.com/SamZadbuke/oibsip_task4.git
   cd email-spam-detection
   ```

2. Install the required libraries:

   ```bash
   pip install pandas streamlit scikit-learn
   ```

3. Download the email dataset (e.g., "email_spam.csv") and place it in the same directory as the Python script.

4. Run the application:

   ```bash
   streamlit run email_spam_detection.py
   ```

The web application will open in your default web browser.

## Features

- Display the accuracy of the Naive Bayes classifier.
- Show a bar chart with the count of Spam and Ham emails in the dataset.
- Allow users to test an email for spam by entering text and clicking the "Predict" button.
- Display the prediction result (spam or not spam) for the input text.

## Dependencies

- Python 3.6+
- pandas
- streamlit
- scikit-learn

## Usage

1. Upon running the application, you will see a title and a brief description of what the tool does.

2. The accuracy of the Naive Bayes classifier on the dataset is displayed at the top of the page.

3. A bar chart shows the count of Spam and Ham emails in the dataset.

4. You can test an email for spam by entering text in the provided text area and clicking the "Predict" button. The prediction (spam or not spam) will be displayed below.


