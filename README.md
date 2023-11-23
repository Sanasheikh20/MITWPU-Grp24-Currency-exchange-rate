# MITWPU-Grp24-Currency-exchange-rate
Currency Exchange Rate Variation Dashboard
This is a simple web application built with Dash and Plotly to visualize currency exchange
rate variations over time. The application allows users to select a date, time span, and
currencies to view the exchange rate variation between the selected currencies.
Getting Started
To run this application, you need to have Python installed on your machine. Additionally,
install the required libraries by running:
pip install dash pandas plotly
Clone the repository and navigate to the project directory:
git clone https://github.com/your_username/your_repository.git
cd your_repository
Run the application:
python your_script_name.py
Visit `http://127.0.0.1:8070/` in your web browser to interact with the application.
Features
- Date Selection: Choose a specific date using the date picker.
- Time Span Selection: Select a time span (Weekly, Monthly, Quarterly, Yearly) to analyze
exchange rate trends.
- Currency Selection: Pick two currencies to compare their exchange rates over the selected
time period.
- Graphical Representation: View the exchange rate variation between the selected
currencies with an interactive line chart.
- Additional Information: The application provides information about the selected time period
and highlights the highest and lowest values.
Code Structure
- Data Loading: Reads and concatenates CSV files containing exchange rate data.
- Data Cleaning: Handles missing values by filling them with the mean of the respective
currency.

- Dash Application Layout: Defines the structure of the web application using HTML and
Dash components.
- Callback Function: Updates the graph based on user inputs (date, time span, currencies).
Customization
Feel free to customize this application to meet your specific needs. You can modify the code
to include additional features, change the layout, or enhance the visualizations.
Acknowledgments
- [Dash Documentation](https://dash.plotly.com/)
- [Plotly Documentation](https://plotly.com/python/)
- [Pandas Documentation](https://pandas.pydata.org/pandas-docs/stable/)
Happy coding!
