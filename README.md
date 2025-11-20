# DataBreach Dashbaord


## Data Breach Visualization Dashboard

<img width="1566" height="840" alt="Screenshot 2025-11-20 084708" src="https://github.com/user-attachments/assets/1873c63c-5330-495d-98ab-97494e2824f7" />
<img width="1456" height="730" alt="Screenshot(1) 2025-11-20 084725" src="https://github.com/user-attachments/assets/3332a9f0-05e6-45a0-90f5-5b50507a154f" />


A simple and interactive Dash + Plotly web dashboard that visualizes data breach statistics using bar charts, pie charts, and line charts.
The UI is enhanced with a custom CSS theme included inside the assets/ folder.


## 🚀 Features

- Bar Chart
Displays the number of breached records per company.

- Pie Chart
Shows distribution of impact across different organization types.

- Line Chart
Visualizes breach records across multiple years.

- Custom Dark Theme
Includes a custom style.css file to enhance layout and appearance:
Dark gradient background
Typography styling
Button styles
Custom graph container layout
Responsive container grid


## 📁 Project Structure

Data-Breach-Dashboard/
│
├── app.py                 # Main Dash application
├── Top20.csv              # Data source for visualizations
│
└── assets/
    └── style.css          # Custom CSS automatically loaded by Dash

Dash automatically loads all .css or .js files placed inside the assets folder.
You don’t have to import the CSS manually — Dash handles it for you.


## 🐍 Installation & Setup

1️. Install Dependencies
pip install dash pandas plotly

2️. Run the Application
python app.py

3️. Open in Browser
Dash will start a local server.
Go to:
http://127.0.0.1:8050/


