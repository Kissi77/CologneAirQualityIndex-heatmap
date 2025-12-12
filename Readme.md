🌍 Cologne PM2.5 → AQI Time-Lapse Heatmap

This project visualizes PM2.5 air-quality data from several Cologne monitoring stations and converts the values into AQI (Air Quality Index).
An interactive time-lapse heatmap is generated using Folium to show how air quality changes over time.

# Cologne Air Quality Index Heatmap

This project visualizes PM2.5 air quality data for Cologne using Python, Pandas, and Folium.

- **Data Source:** [Luftqualität NRW](https://luftqualitaet.nrw.de/lqitabelle.php)

- **Interactive AQI Map:**  
  [Click here to view the map](https://kissi77.github.io/CologneAirQualityIndex-heatmap/)

The data is publicly accessible and free to download.
A ZIP copy of the dataset used in this project is included in the repository for reproducibility.

📌 Features

Converts PM2.5 values to AQI

Generates an animated heatmap with a time slider

Adds station markers with AQI popups

Displays permanent station labels

Includes a custom AQI color legend

Exports to an interactive HTML file

▶️ How to Run

Install required libraries:

pip install pandas folium numpy


Run the script:

MonitoringAirQuality_Cologne_ipynb


This generates:

Cologne_AQI_heatmap.html


Open the HTML file in your browser to explore the map.

📂 Files in This Project
README.md
MonitoringAirQuality_Cologne_ipynb
Cologne_Pm2.5_Data


🛠 Technologies Used

Python

Pandas

NumPy

Folium

HeatMapWithTime plugin

📄 License

This project is open-source.
Please retain the data-source attribution above in derivative works.


