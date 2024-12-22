# Live-Dashboard-of-COVID-19

The Live COVID-19 Dashboard is an interactive web application built with Python that provides real-time updates and visualizations about the ongoing global pandemic. It aggregates COVID-19 data from reliable sources like the Johns Hopkins University API or COVID-19 Data API, and dynamically displays key statistics on the dashboard.

Key Features:
Real-Time Data Updates:

The dashboard fetches live data for cases, recoveries, deaths, and vaccinations worldwide, as well as for individual countries, states, or regions.
Data is updated at regular intervals (e.g., every hour) to provide accurate, up-to-date information.
Global and Local View:

Users can toggle between global statistics and more detailed country- or region-specific data.
A world map visualization allows users to view the number of cases, recoveries, and deaths geographically.
Interactive Visualizations:

Interactive charts and graphs (using Plotly or Matplotlib) display trends of COVID-19 cases over time, including daily new cases, recovery rates, and death tolls.
Pie charts to represent the proportion of cases, recoveries, and deaths.
Bar charts and line charts to showcase global or country-specific trends.
Data Filtering:

Users can filter the data based on time ranges (e.g., daily, weekly, monthly) or by region/country for customized insights.
Ability to sort countries by the total number of cases, deaths, and recoveries.
Search Functionality:

A search bar allows users to search for specific countries or regions to get a detailed report of the latest statistics for that location.
COVID-19 Trends and Predictions:

Incorporates machine learning algorithms to show predictions on future trends, like case growth or recovery rates, using models such as ARIMA or Facebook Prophet.
News and Updates Section:

Displays the latest news and government advisories related to COVID-19, keeping users informed about new developments.
User-Friendly Interface:

The dashboard features an intuitive design, making it easy for both technical and non-technical users to navigate.
A responsive layout ensures that it works seamlessly on desktop and mobile devices.
Technologies Used:
Backend:

Python as the core programming language.
Flask or Django framework to create a lightweight web application.
Requests library to fetch real-time data from APIs.
Frontend:

HTML/CSS for basic web structure and styling.
JavaScript for dynamic and interactive content.
Bootstrap for responsive design.
Data Visualization:

Plotly or Matplotlib for creating interactive charts.
Folium for map visualizations.
API Integration:

Data is retrieved from APIs like COVID-19 API, Johns Hopkins University data, or other open sources that provide real-time COVID-19 statistics.
Deployment:

The dashboard can be deployed using Heroku, AWS, or Google Cloud Platform to make it publicly accessible.
