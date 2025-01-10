
# NYC Taxi Exploratory Data Analysis

This repository contains the project work for exploratory data analysis (EDA) of the 2017 New York City Taxi and Limousine Commission dataset. The project is part of the Automatidata Course 3 lab, focusing on data structuring, cleaning, and visualization using Python and Tableau.

## Project Overview

The goal of this project is to analyze the NYC TLC dataset to understand taxi ridership patterns and derive insights using:
- Data cleaning and preparation
- Visualization of key metrics such as trip distances, ride counts, and revenues
- Accessibility-focused Tableau dashboards for presenting findings

## Tools and Libraries
- Python: Pandas, Matplotlib, Seaborn, NumPy, Datetime
- Tableau Public: For interactive data visualization
- Jupyter Notebook: For Python-based analysis

## Key Features
1. **Data Cleaning:**
   - Handling outliers
   - Addressing invalid data such as zero passenger counts
   - Converting date columns for temporal analysis

2. **Visualizations in Python:**
   - Box plots, histograms, bar charts, and scatter plots
   - Analysis by months, days, and trip characteristics

3. **Accessibility in Tableau:**
   - Interactive NYC map of taxi trips by month
   - Insights tailored for visually impaired stakeholders

## Project Structure
- `data/`: Contains the dataset (not included here; see course materials).
- `notebooks/`: Jupyter notebooks for the EDA and visualizations.
- `tableau/`: Tableau workbook files and exported dashboards.
- `README.md`: This documentation.

## Instructions
1. Clone this repository:
   ```bash
   git clone https://github.com/talharauf15/NYC_Taxi_Exploratory_Data_Analysis.git
   ```
2. Install the required Python libraries:
   ```bash
   pip install pandas matplotlib seaborn numpy
   ```
3. Open the Jupyter notebooks in the `notebooks/` directory to explore the analysis.
4. Visit [Tableau Public](https://public.tableau.com/) to view the interactive dashboards.

## Insights and Conclusions
- The majority of trips are under 5 miles.
- Revenue and ride counts fluctuate significantly across months and days of the week.
- Outliers and anomalies, such as zero-distance trips, require further investigation.

## Acknowledgements
This project is part of the Coursera "Automatidata: Go Beyond the Numbers" course. Special thanks to Automatidata and the NYC Taxi and Limousine Commission for the dataset.

## License
This project is for educational purposes and follows the [Coursera terms of use](https://www.coursera.org/about/terms).
