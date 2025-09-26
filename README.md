# 📊 Exploring Airbnb Market Trends with Python

## Project Overview

This repository contains a comprehensive data analysis case study exploring the market trends, pricing strategies, and key factors influencing Airbnb listings. The goal is to extract actionable insights from real-world listing data to understand the dynamics of the short-term rental market.

The primary deliverable is a Jupyter Notebook (`exploring-airbnb-market-trends-with-python.ipynb`) that documents the end-to-end data science process, from cleaning and exploration to visualization and analysis.

## 🎯 Key Objectives

The analysis focuses on answering critical questions such as:

* **Geographic Distribution:** Where are the majority of listings concentrated, and how does location impact price?
* **Pricing Analysis:** What are the average listing prices, and what factors (e.g., room type, number of bedrooms) have the strongest correlation with price?
* **Review and Availability Trends:** How do review scores relate to pricing and occupancy rates?
* **Property Characteristics:** Which amenities and property types are most popular and profitable?

## 🛠️ Technology and Libraries

The project is built using Python and the following key libraries:

* **Data Manipulation:** `pandas`, `numpy`
* **Data Visualization:** `matplotlib`, `seaborn`
* **Interactive Analysis (Optional):** If you used tools like Plotly or Folium, you can add them here.

## 📁 Repository Structure

* `exploring-airbnb-market-trends-with-python.ipynb`: The main Jupyter Notebook containing all the code, analysis, visualizations, and conclusions.
* `[data_file_name.csv]`: The raw or cleaned dataset used for the analysis (e.g., `airbnb_data.csv`).
* **[Optional]** `images/`: A directory for saving key visualizations from the notebook to display in the README.

***Note:*** *Replace `[data_file_name.csv]` with the actual file name of your dataset, if it's included in the repository.*

## 🚀 How to Run the Project Locally

To reproduce this analysis on your own machine, follow these steps:

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/Roberto-Luis-Rodriguez/Airbnb-Market-Trends.git](https://github.com/Roberto-Luis-Rodriguez/Airbnb-Market-Trends.git)
    cd Airbnb-Market-Trends
    ```
2.  **Set up the environment:**
    * It is recommended to use a virtual environment.
    * Install the required libraries (e.g., in a new environment):
        ```bash
        pip install pandas numpy matplotlib seaborn jupyter
        ```
3.  **Run the Notebook:**
    ```bash
    jupyter notebook exploring-airbnb-market-trends-with-python.ipynb
    ```
    The notebook will open in your web browser, allowing you to execute the cells and review the analysis.

  ## Key Finding: Geographic Price Variation

!(images/Average Price per Borough.png)
!(images/Average Price per Room Type.png)
!(images/Top 20 Words in Listing Descriptions.png)
!(images/Top Ten Neighborhoods with Lowest Average Prices.png)

Fix: Display price map image in README<img width="848" height="625" alt="Top Ten Neighborhoods with Lowest Average Prices" src="https://github.com/user-attachments/assets/fd956575-5da2-43ea-a735-5ba5193326a2" />
<img width="912" height="547" alt="Top 20 Words in Listing Descriptions" src="https://github.com/user-attachments/assets/0852a58d-d47d-4b95-9a53-dd2689606f80" />
<img width="988" height="590" alt="Average Price per Room Type" src="https://github.com/user-attachments/assets/ff4a5c70-0dd0-4746-abf0-e97e730d5e1d" />
<img width="695" height="470" alt="Average Price per Borough" src="https://github.com/user-attachments/assets/d25e2b49-4cdc-4bea-aca3-d5d7a188088e" />

--- Add comprehensive README.md
