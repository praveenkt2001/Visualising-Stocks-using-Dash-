Visualising Stocks using Dash
This project is a web application developed with the Dash framework in Python, designed to assist users in visualizing and forecasting stock market data. By entering a company's stock code and selecting a date range, users can view historical stock prices and generate forecasts using machine learning models.

Features
Stock Data Visualization: Input a company's stock code and date range to view historical stock prices.

Stock Price Forecasting: Utilize machine learning models to predict future stock prices based on historical data.

Project Structure
app.py: The main application file that initializes and runs the Dash web server.

model.py: Contains functions for fetching stock data and implementing machine learning models for forecasting.

requirements.txt: Lists all the Python dependencies required to run the application.

Procfile: Configuration file for deploying the application on platforms like Heroku.

styles.css: Contains CSS styles for enhancing the application's user interface.

Getting Started
Prerequisites
Python 3.x

pip (Python package installer)

Installation
Clone the Repository:

bash
Copy
Edit
git clone https://github.com/praveenkt2001/Visualising-Stocks-using-Dash-.git
cd Visualising-Stocks-using-Dash-
Install Dependencies:

bash
Copy
Edit
pip install -r requirements.txt
Running the Application
Execute the following command to start the Dash application:

bash
Copy
Edit
python app.py
After running the command, open your web browser and navigate to http://127.0.0.1:8050/ to access the application.

Usage
Input Stock Code: Enter the stock code (ticker symbol) of the company you wish to analyze.

Select Date Range: Choose the start and end dates for the historical data you want to visualize.

View Data: The application will display the historical stock prices for the selected company and date range.

Forecast Prices: Utilize the forecasting feature to predict future stock prices based on historical data.

Dependencies
The application relies on the following Python packages:

dash: For building the web application.

pandas: For data manipulation and analysis.

plotly: For creating interactive visualizations.

scikit-learn: For implementing machine learning models.

These dependencies are specified in the requirements.txt file.

Deployment
To deploy this application on a platform like Heroku:

Install the Heroku CLI: Heroku CLI Installation Guide

Login to Heroku:

bash
Copy
Edit
heroku login
Create a New Heroku App:

bash
Copy
Edit
heroku create your-app-name
Deploy the Application:

bash
Copy
Edit
git push heroku main
Open the Application:

bash
Copy
Edit
heroku open
