# IBM Data Science Professional Certificate - Capstone Project

## Project Overview
This repository contains the final capstone project for the IBM Data Science Professional Certificate. The primary goal of this project is to predict whether the Falcon 9 first stage will land successfully. SpaceX advertises Falcon 9 rocket launches on its website with a cost of 62 million dollars; other providers cost upward of 165 million dollars each, much of the savings is because SpaceX can reuse the first stage. By predicting a successful landing, we can determine the cost of a launch.

## Data Sources
The data used in this project was collected from two primary sources:
* **SpaceX API:** To gather historical launch data, rocket specifications, and payload details.
* **Wikipedia Scraping:** To extract supplementary launch records and core details using BeautifulSoup.

## Methodology & Project Steps
The project follows the standard data science workflow across several Jupyter Notebooks:
1. **Data Collection:** Retrieving data via API endpoints and web scraping.
2. **Data Wrangling:** Cleaning the dataset, handling missing values, and engineering the target success label (`Class`).
3. **Exploratory Data Analysis (EDA):** Using SQL queries and visualization tools (Seaborn/Matplotlib) to discover trends.
4. **Interactive Map Analytics:** Utilizing Folium to visualize launch site locations and proximity to coastlines or highways.
5. **Dashboard Application:** Building a Plotly Dash application for real-time interactive data filtering.
6. **Predictive Modeling:** Training and evaluating machine learning models (Logistic Regression, Support Vector Machine, Decision Tree, and K-Nearest Neighbors).

## Key Results
* Best Performing Model: all models achieved the highest accuracy of 83,33% on test data and similar confussion matrixes, with decision tree classifier having slightly higher results on training data.
* Crucial Factors: Launch site proximity to highways/railways and payload mass played significant roles in landing success rates.

## Libraries and Tools Used
* **Languages:** Python, SQL
* **Data Libraries:** Pandas, NumPy
* **Visualization:** Matplotlib, Seaborn, Folium, Plotly Dash
* **Machine Learning:** Scikit-learn

## How to Run the Notebooks
1. Clone this repository to your local machine.
2. Install the required dependencies: `pip install pandas numpy scikit-learn matplotlib seaborn folium dash`
3. Run the Jupyter Notebooks sequentially from step 1 to step 6.

---
Author: Dimitri Nadiradze 
Date: July, 2025 
Completed as part of the Coursera IBM Data Science Professional Certificate program.

