# Project-My-Daily-Internet-Acitivity
A Python-based graphical user interface (GUI) application for analyzing daily internet usage data. This project allows users to load, view, sort, and visualize their internet usage statistics for apps like Instagram, YouTube, and WhatsApp.

Features

Load CSV Data: Import and clean data from a CSV file containing daily internet usage.

View Data: Display the cleaned data in a tabular format.

Sort Data: Sort internet usage data by Instagram usage in descending order.

Data Visualization: Generate:

Stacked Bar Chart: Shows daily usage for Instagram, YouTube, and WhatsApp.

Pie Chart: Displays total usage distribution by app.

Prerequisites

To run this application, you need:

Python 3.7 or higher

Required libraries:

tkinter (built-in with Python)

pandas

matplotlib

Install the required libraries with the following command:
pip install pandas matplotlib

Setup Instructions:
Place your daily internet usage CSV file in the project directory. The CSV should have the following structure:

Date

Instagram

YouTube

WhatsApp

01-01-2025

50 MB

120 MB

80 MB

The application expects columns named Date, Instagram, YouTube, and WhatsApp.

Usage values should include units like MB (e.g., 50 MB).

Run the application:
python My\ DAily\ Data\ activityGUI.py

                                 Usage

1- Load Data:

Click on the "Load CSV" button.

Select your CSV file. The application will clean and display the data in a table.

2- Sort Data:

Click on "Sort Data" to sort the records by Instagram usage in descending order.

3- Visualize Data:

Click on "Show Visualizations" to:

View a stacked bar chart of daily usage.

View a pie chart of total usage distribution across apps.

Code Structure

My DAily Data activityGUI.ipynb: Main Jupyter Notebook containing the GUI application code.

DailyInternetUsage.csv: Sample CSV file with internet usage data.

Key Components

Data Loading:

Reads CSV data using pandas.

Cleans the data (e.g., removes MB units and converts columns to numerical values).

GUI:

Built with tkinter for an interactive user interface.

Includes buttons for loading data, sorting data, and displaying visualizations.

Visualization:

Stacked bar chart for daily app usage.

Pie chart for total usage distribution.

Example

1- Load the data:
Data loaded successfully!
Sample Table:

Date                 01-01-2025

Instagram            50MB
YouTube              120MB
WhatsApp             80MB 


2- Sort the data

3- View visualizations:

Stacked Bar Chart:
Pie Chart:
