# Avocado Dataset Analysis
This repository contains an analysis of the avocado dataset, exploring the pricing trends over time and making predictions using the Prophet library.

## Avocado Dataset
The dataset (avocado.csv) contains information about avocado sales, including the following columns:

Date: Date of the recorded data
AveragePrice: Average price of avocados
Total Volume: Total volume of avocados sold
4046, 4225, 4770: Sales volume of different types of avocados
Total Bags: Total bags sold
Small Bags, Large Bags, XLarge Bags: Volume of different bag sizes sold
type: Type of avocado (e.g., conventional or organic)
year: Year of the record
region: Region where the avocados were sold

## Jupyter Notebook (`code.ipynb`)
Sections in the Notebook
1. **Importing the Dataset and Packages:** Loading necessary libraries and importing the avocado dataset using Pandas.
2. **Exploring and Visualizing the Dataset:** Initial exploration of the dataset, checking the first few rows, and visualizing the data's trend over time and distribution across regions.
3. **Preparing Data for Forecasting:** Formatting the data for Prophet by selecting the necessary columns and renaming them.
4. **Making Predictions with Prophet:** Utilizing the Prophet library to train a model on the dataset and forecasting future avocado prices.
5. **Visualizing Predictions:** Plotting the predicted avocado prices over time and visualizing trend components.

## Usage
1. Clone the repository:
   ```
   git clone https://github.com/Devansh-Gupta-Official/facebook-prophet-avocadoprice.git
   ```
2. Install necessary Python dependencies:
   ```
   pip install -r requirements.txt
   ```
3. Open and run the Jupyter Notebook (code.ipynb) using Jupyter or any compatible environment.
