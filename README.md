# Data Visualization Project

## Overview
This project demonstrates how to create dynamic and comprehensive visualizations for any dataset using Python. It includes histograms, correlation heatmaps, scatter plots, bar charts, and line charts. The code automatically handles numeric and categorical columns to make visualization easy and flexible.

## Features
- **Histograms:** Automatically plots distributions of all numeric features.
- **Correlation Heatmap:** Visualizes relationships and correlations between numeric features.
- **Scatter Plots:** Plots pairwise relationships between numeric features.
- **Bar Charts:** Compares numeric values across categorical features.
- **Line Plots:** Shows trends of numeric features over the dataset index.

## Libraries Used
- [Pandas](https://pandas.pydata.org/) – For data manipulation and analysis.
- [Matplotlib](https://matplotlib.org/) – For plotting and visualizations.
- [Seaborn](https://seaborn.pydata.org/) – For advanced and aesthetic statistical visualizations.

## How to Use
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/your-repo-name.git

   Navigate to the project folder:

cd your-repo-name


Install required libraries (if not already installed):

pip install pandas matplotlib seaborn


Replace the sample dataset in data_visualization.py with your own dataset:

df = pd.read_csv("your_dataset.csv")


Run the script:

python data_visualization.py

Example Visualizations

Histograms of numeric features

Correlation heatmap

Scatter plots for numeric pairs

Bar charts comparing numeric and categorical features

Line plots showing trends over the index

Notes

The code automatically identifies numeric and categorical columns.

Scatter plots are generated for all numeric column combinations.

Bar charts are generated for all categorical-numeric pairs.

Line plots are generated for all numeric columns over the dataset index.

Author

Arsal Tariq Chohan

License

This project is open-source and available under the MIT License.
