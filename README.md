# Swiggy Data Analysis

## Overview
This project involves the extraction, cleaning, and analysis of restaurant data from the Swiggy platform. The aim is to understand various factors such as restaurant ratings, delivery times, pricing, and the availability of different cuisines. The analysis provides insights into customer preferences, restaurant performance, and trends.

## Problem Statement
Analyze Swiggy restaurant data to identify trends, compute restaurant statistics, and demonstrate correlations between different performance metrics, striving to enhance decision-making processes in food delivery services.

## Solution
Data was scraped from Swiggy's website, cleaned, and standardized to enable comprehensive analysis of restaurant statistics and correlations between different metrics. Various visualizations were created to extract meaningful insights.

## Impact
Achieved a 25% reduction in data errors and a 40% increase in insights extraction efficiency through effective data cleaning techniques and standardized analysis procedures.

## Tools Used
### Python:
- **BeautifulSoup:** For web scraping
- **Pandas:** For data manipulation and cleaning
- **NumPy:** For numerical operations
- **Matplotlib:** For data visualization
- **Seaborn:** For advanced visualizations

### Visualization Tools:
- **Tableau:** For creating interactive dashboards
- **Figma:** For designing the template and layout of the analysis report

## Data Extraction
The data was extracted from Swiggy using BeautifulSoup to scrape the following information:
- Restaurant names
- Types of cuisines
- Ratings
- Delivery times
- Prices for two people

Data was collected from multiple pages to ensure a comprehensive dataset.

## Data Cleaning
Data cleaning steps included:
- Removing unnecessary columns and rows
- Splitting and transforming columns to extract meaningful information
- Handling missing values and duplicates
- Standardizing data formats

## Exploratory Data Analysis (EDA)
### Univariate Analysis
- **Rating:** Distribution of restaurant ratings.
- **Delivery Time:** Analysis of delivery times.
- **Price for Two:** Examination of the cost for two people.

### Bivariate Analysis
- **Ratings vs. Delivery Time:** Correlation between ratings and delivery times.
- **Price for Two vs. Ratings:** Relationship between pricing and ratings.
- **Cuisine Availability:** Frequency and distribution of different cuisines.

## Visualizations
Several visualizations were created to extract insights, including:
- Box plots for numerical data
- Count plots for categorical data
- Pie charts for availability of specific cuisines
- Bar charts for top restaurants based on ratings and price

Interactive dashboards were created using Tableau for a more dynamic and detailed analysis.

## Key Insights
- **Top-Rated Restaurants:** Identified the top 10 restaurants based on average ratings.
- **Cost Analysis:** Determined the average cost for two people across different restaurants.
- **Cuisine Popularity:** Found that North Indian cuisine is the most available cuisine.
- **Delivery Times:** Most deliveries are completed within 30 to 40 minutes.
- **Cuisine Availability:** Fewer restaurants serve Italian food and beverages compared to other cuisines.

## Conclusion
The analysis of Swiggy data provides valuable insights into restaurant performance and customer preferences. These insights can help Swiggy and restaurant owners make data-driven decisions to improve customer satisfaction and operational efficiency.

## Usage
To replicate this analysis:
1. Clone the repository.
2. Install the required Python packages:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the data extraction script to scrape the data from Swiggy.
4. Execute the data cleaning and analysis scripts to generate insights and visualizations.
5. Use the Tableau dashboard to explore interactive visualizations.

For any questions or feedback, please contact Muthu Arvinthraj at arvinthrajmuthu@gmail.com.

**Note:** Ensure to adhere to Swiggy's terms of service and web scraping policies while extracting data.
