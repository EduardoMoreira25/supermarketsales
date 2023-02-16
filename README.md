# Sales Dashboard
This code is a Streamlit application that reads an Excel file containing sales data, filters the data based on user-selected parameters, and displays the results in a dashboard. The dashboard displays the total sales, average rating, and average sales per transaction of the filtered data. It also shows the sales by product line and by hour in separate bar charts.

## Requirements
This code requires the following Python packages to be installed:

pandas
openpyxl
plotly-express
streamlit
You can install these packages using pip.

## Usage
To use this code, follow these steps:

Install the required packages using pip.
Save the Excel file containing the sales data as supermarkt_sales.xlsx in the same directory as this Python script.
Run the Python script using streamlit run [filename].py.
The Streamlit application will open in a browser window.
Use the sidebar to filter the data based on city, customer type, and gender.
The dashboard will update based on your filter selections.
