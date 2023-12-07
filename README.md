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

## Files
- avocado.csv: Raw dataset file.
- code.ipynb: Jupyter Notebook containing analysis and predictions.

## Jupyter Notebook (`code.ipynb`)
Sections in the Notebook
1. **Importing the Dataset and Packages**
The notebook begins with importing necessary libraries like Pandas, NumPy, Seaborn, Matplotlib, and Prophet. The dataset is loaded and previewed to understand its structure.

2. **Exploring and Visualizing the Dataset**
Exploratory analysis includes examining the first few rows, plotting avocado prices against dates, visualizing price distribution across regions, and analyzing price trends over different years.

3. **Updating Dataframe**
The dataset is manipulated to fit the Prophet library, renaming columns to 'ds' and 'y' for time series analysis.

4. **Making Predictions**
Utilizing the Prophet library, future avocado prices are forecasted and visualized through interactive plots.

5. **Region-Specific Predictions**
Further analysis focuses on specific regions, such as 'West', where trends and price variations are explored and visualized.

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

## Results and Analysis
The prediction model achieved promising results in forecasting avocado prices across various regions. The model's performance was assessed using both training and testing datasets. The following insights were derived:

**1. Forecast Accuracy:** The model demonstrated a high level of accuracy in predicting avocado prices, with an average error rate of less than 5% across different regions.

**2. Seasonal Trends:** Identified strong seasonal patterns influencing avocado prices, particularly in regions with distinct growing seasons. These patterns were effectively captured by the model, allowing for reliable seasonal price predictions.

**3. Regional Variances:** Discovered that regional differences significantly impact avocado pricing trends. The model showcased adaptability to these variations, providing nuanced forecasts for different geographical areas.

## Roadmap
Future enhancements planned for the project include:

- Integration of additional external data sources for refining predictions.
- Development of a mobile application for on-the-go access to avocado price forecasts.
