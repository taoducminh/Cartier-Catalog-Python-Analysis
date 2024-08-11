
# Cartier Catalog Python Analysis

## Overview

This project focuses on analyzing a dataset of Cartier jewelry products. The analysis includes investigating various aspects of the products, such as the types of gems used, the most common metals, the average price of jewelry by metal, and more. The goal is to extract meaningful insights that can inform business decisions or further research.

## Project Structure

- **Data Loading and Preparation:** The dataset is loaded and initial data preparation steps are carried out, including splitting tags into individual components (e.g., metal type, gems) and cleaning the data for analysis.

- **Analysis Questions:**
  1. **What types of gems are used in the products?**
  2. **Which metals are used most frequently?**
  3. **What is the average price of jewelry by metal?**
  4. **How many gems are there in each type of product?**
  5. **What is the average price of jewelry in each product category?**
  6. **What are the most expensive types of gems?**

- **Data Visualization:** The project uses Seaborn and Matplotlib to visualize the distribution of gems, metals, and prices across different categories.

## Key Libraries

- `pandas`: For data manipulation and analysis.
- `seaborn`: For creating attractive and informative statistical graphics.
- `matplotlib`: For additional plotting capabilities.

## Data Source

The dataset used in this analysis is assumed to be stored in a CSV file named `cartier_catalog.csv`. The notebook reads this file into a Pandas DataFrame for processing.

## Instructions for Running the Project

1. **Clone the Repository:**
   ```
   git clone [repository_url]
   cd Cartier_Catalog_Python_Analysis
   ```

2. **Install Dependencies:**
   Make sure you have Python installed. Then, install the necessary packages using pip:
   ```
   pip install pandas seaborn matplotlib
   ```

3. **Run the Notebook:**
   Open the notebook in Jupyter or any compatible environment and run the cells step-by-step to perform the analysis:
   ```
   jupyter notebook Cartier_Catalog_Python_Analysis.ipynb
   ```

## Visualizations

The notebook generates several plots, including:
- Bar charts showing the count of different types of gems.
- Bar charts representing the mean price of jewelry by metal.
- Bar charts comparing the distribution of gem types across product categories.

## Conclusions

This analysis provides insights into the materials and pricing of Cartier jewelry, highlighting trends in the use of metals and gems. Such insights can be valuable for both business strategy and academic research.

## Future Work

Future analyses could include:
- Detailed analysis of pricing strategies based on geographic location.
- Time-series analysis to track changes in product offerings over time.
- Predictive modeling to forecast future trends in jewelry design and pricing.

## License

This project is licensed under the MIT License - see the LICENSE file for details.
