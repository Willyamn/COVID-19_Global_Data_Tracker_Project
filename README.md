# COVID-19_Global_Data_Tracker_Project
# COVID-19 Global Data Tracker

A Jupyter Notebook project that tracks and visualizes **COVID-19 data worldwide** using the latest dataset from [Our World in Data](https://ourworldindata.org/covid-19).  

This project provides insights into global trends, top affected countries, and relationships between COVID-19 cases and deaths.

---

## Objectives

- Load and explore COVID-19 data from a reliable source.
- Perform basic exploratory data analysis (EDA).
- Visualize global trends, top affected countries, and relationships between cases and deaths.
- Draw insights to understand the global impact of COVID-19.

---

## Tools and Libraries Used

- **Python 3.x**
- **Jupyter Notebook** for interactive analysis
- **Pandas** for data handling and manipulation
- **Matplotlib** for plotting line and scatter charts
- **Seaborn** for enhanced visualization styling

---

## How to Run / View the Project

1. Clone this repository:

bash
git clone <repository-url>
Navigate to the project folder and open the notebook:

cd covid19-global-tracker
jupyter notebook


Open covid19_tracker.ipynb and run all cells from top to bottom.
The notebook will automatically fetch the latest COVID-19 dataset from Our World in Data.

## Key Features & Visualizations

Global Cases Over Time: Line chart showing worldwide total COVID-19 cases.

Global Deaths Over Time: Line chart showing worldwide total COVID-19 deaths.

Top 10 Countries by Cases: Bar chart highlighting countries most affected by the pandemic.

Total Cases vs Total Deaths: Scatter plot for the latest date, colored by continent.

Summary Statistics: Latest global totals and top countries by cases and deaths.

## Insights / Reflections

Global COVID-19 cases and deaths have distinct waves over time.

Countries with higher total cases generally have higher total deaths, though fatality rates differ.

Visualization helps identify trends, peaks, and the pandemic’s impact across regions.

The tracker is dynamic and updates as new data becomes available.

## Dataset

Source: Our World in Data COVID-19 Dataset

Format: CSV

Key columns used: country, date, total_cases, new_cases, total_deaths, new_deaths, continent, population.

## License

This project is open-source and licensed under the MIT License.
