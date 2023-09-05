# Email Spam Detection Using Machine Learning

Welcome to the Car Price Estimation Tool! This web application utilizes a machine learning model to estimate car prices based on various features. Users can input car details, and the tool will generate a price estimate. In addition, the tool provides visualizations to explore the relationships between numeric features and car prices.

## Features

- **Data Preprocessing:** The application loads and preprocesses the car price dataset, including one-hot encoding of categorical features.

- **Machine Learning Model:** It uses a Random Forest Regressor to predict car prices.

- **Visualization:** Users can visualize how numeric features correlate with car prices using scatter plots.

- **Prediction:** After inputting car details, the tool provides a predicted car price based on the trained model.

## How to Use

1. Clone this repository to your local machine.

2. Install the required libraries if you haven't already:
   ```
   pip install pandas streamlit scikit-learn matplotlib
   ```

3. Run the Streamlit app:
   ```
   streamlit run app.py
   ```

4. Open the application in your web browser, and you'll see the Car Price Estimation Tool.

5. Enter car details, including numeric features and select categorical features from the dropdowns.

6. Click the "Predict" button to see the estimated car price.

## Dependencies

- pandas
- streamlit
- scikit-learn
- matplotlib

## Project Structure

- `app.py`: The main Streamlit application script.
- `car_price.csv`: The dataset containing car price and features.
- `README.md`: This README file.

## Acknowledgments

This project is for educational purposes and demonstrates how to create a simple web application for car price estimation using machine learning and Streamlit.
