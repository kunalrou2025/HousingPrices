# Housing Price Data Analysis

## Overview
This project aims to analyze a dataset of housing prices, with multiple features such as house area, cost, locality, number of bedrooms, number of bathrooms, and more. Using various data visualization techniques, the project explores the relationship between these features and the sale price of houses. 

The analysis includes plotting graphs, scatter plots, pie charts, and other data visualizations to understand the patterns and trends in the housing market.

## Key Features
- **Sale Price Prediction**: Analyzes the relationship between house price and various attributes like area, number of bedrooms, and more.
- **Visualizations**: Provides various plots such as scatter plots, pie charts, and bar graphs to show trends and correlations.
- **Data Insights**: Delivers insights into how different factors influence house prices, including renovation status, square footage, and location.

## Dataset Information
The dataset contains the following columns:
- **ID**: Unique identifier for each house transaction.
- **Date**: Date when the house was sold.
- **Sale Price**: The price at which the house was sold.
- **No of Bedrooms**: The number of bedrooms in the house.
- **No of Bathrooms**: The number of bathrooms in the house.
- **Flat Area (in Sqft)**: The area of the house in square feet.
- **Lot Area (in Sqft)**: The area of the land the house is built on, in square feet.
- **No of Floors**: The number of floors in the house.
- **Waterfront View**: Whether the house has a waterfront view (Yes/No).
- **Overall Grade**: The overall grade of the house.
- **Renovated Year**: The year the house was renovated (if applicable).
- **Zipcode**: The zip code where the house is located.
- **Latitude**: Latitude of the house location.
- **Longitude**: Longitude of the house location.

### Descriptive Statistics
The dataset contains 21,613 entries with the following statistical properties:
- **Average Sale Price**: $540,198
- **Average Flat Area**: 2,079.93 Sqft
- **Average Lot Area**: 15,107.76 Sqft
- **Average Age of House**: 46.99 years
- **Renovation Year**: Most houses were renovated around 1986
- **Most Frequent Zip Code**: 98077

## Visualizations
- **Scatter Plot**: A scatter plot showing the relationship between the house's flat area and its sale price.
- **Pie Chart**: A pie chart showing the percentage of houses with and without a waterfront view.
- **Bar Graph**: A bar graph showing the average sale price by the number of floors in the house.
- **Heatmap**: A heatmap visualizing correlations between various features and sale price.

## Steps to Run

1. **Clone the repository**:
    ```bash
    git clone https://github.com/your-username/housing-price-analysis.git
    cd housing-price-analysis
    ```

2. **Install dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

3. **Run the Jupyter Notebook**:
    Open the Jupyter notebook to explore the analysis:
    ```bash
    jupyter notebook
    ```

4. **Data Preprocessing**:
    The notebook includes steps for loading and preprocessing the dataset, cleaning missing or incorrect data.

5. **Exploratory Data Analysis (EDA)**:
    Run the code to generate descriptive statistics, correlation matrices, and visualizations like scatter plots and pie charts.

## Requirements
- Python 3.x
- Jupyter Notebook
- pandas
- numpy
- matplotlib
- seaborn

## Contribution
Feel free to fork the repository, create issues, and submit pull requests to contribute to the analysis or improve the visualizations.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## References
- [Pandas Documentation](https://pandas.pydata.org/)
- [Matplotlib Documentation](https://matplotlib.org/)
- [Seaborn Documentation](https://seaborn.pydata.org/)
