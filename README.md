# KolesaAnalysisProject_15-17-18-19P

## Introduction
This project is a data analysis solution focused on extracting, processing, and visualizing car listings data from kolesa.kz using Jupyter Notebook. It aims to provide insights into vehicle prices, popular models, regions, and trends in the Kazakhstani car market.

## Problem Statement
Car buyers and sellers in Kazakhstan lack easy access to structured, data-driven insights from platforms like Kolesa.kz. This project solves that problem by offering a clear analysis of car listings, helping users make informed decisions based on actual market trends.

## Objectives
- To scrape or import data from Kolesa.kz
- To clean and preprocess the dataset for analysis
- To perform exploratory data analysis (EDA)
- To visualize car market trends (e.g., price by model, region, year)
- To generate useful business or consumer insights

## Technology Stack
Notebook: Jupyter Notebook
Programming Language: Python
Libraries:
• pandas
• numpy
• matplotlib
• seaborn
• BeautifulSoup / requests 
• scikit-learn 

## Installation Instructions

To set up and run the project locally:

1. Clone the repository

git clone https://github.com/yourusername/KolesaAnalysisProject_15-17-18-19P.git

2. Navigate into the project directory

cd KolesaAnalysisProject_15-17-18-19P

3. (Optional) Create and activate a virtual environment

python -m venv venv
source venv/bin/activate       # On Windows: venv\Scripts\activate

4. Install the required Python libraries

pip install -r requirements.txt

5. Launch Jupyter Notebook

jupyter notebook

## Usage Guide
1. After launching Jupyter Notebook:
    ```bash
    jupyter notebook
    ```
2. In the Jupyter interface, open the notebook located at:
    ```
    /src/final_project.ipynb
    ```
3. Run the notebook cells in sequence:
    - Load the dataset from `/data/kolesa_dataset.csv`
    - Clean and preprocess the data
    - Perform analysis (e.g., filtering, grouping, aggregation)
    - Visualize key insights
4. The notebook will generate visualizations such as:
    - Average car prices by brand and model
    - Most frequently listed car models
    - Listings by region
    - Histograms, pie charts, and boxplots
> Make sure that the path to the dataset is correctly referenced in the notebook (e.g., `../data/kolesa_dataset.csv` if opened from `/src`).

## Testing
This project focuses on data analysis, so testing is done manually by checking notebook outputs and graphs.

## References
- kolesa.kz
- pandas documentation
- seaborn documentation
- StackOverflow and Kaggle for analysis inspirations

## Team Members
- Sauatbek Zhanserik 220103332
- Aktureyev Orazali 220103173
- Zharylkassynov Galymbek 220103251
- Abzalbek Mukhamedali 220103209
- Kantore Arman 220103282
