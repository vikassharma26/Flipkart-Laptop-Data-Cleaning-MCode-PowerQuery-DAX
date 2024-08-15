# Flipkart Laptop Data Analysis | Power BI | Power Query | M Code | DAX

This repository showcases the end-to-end data cleaning, transformation, and analysis process performed on a real-life Flipkart laptop dataset. The project highlights the use of **Power BI**, **Power Query**, **M Code**, and **DAX** to handle messy, unstructured data and derive meaningful insights.

## Public Dataset Link : https://www.kaggle.com/datasets/mrmars1010/flipkart-product-datalaptops
## Project Overview

### Dataset:
The dataset used in this project comes from **Flipkart**, one of India's largest e-commerce platforms. Like many real-world datasets, the Flipkart laptop data was unstructured, inconsistent, and required extensive cleaning before it could be analyzed. Key issues included missing values, inconsistent formats, and disorganized product information.

### Objective:
The main objective was to clean and transform this dataset to make it suitable for analysis and visualization, providing actionable insights into:
- Laptop brands with the highest warranties
- Brands with the best customer ratings
- Top laptops based on discounts and ratings
- Warranty comparison with product prices

## Key Skills Highlighted
1. **Power Query & M Code**:
   - Extracted product details like brand, RAM, processor, storage, and warranty from the unstructured product names.
   - Cleaned and standardized columns using **M Code**, handling issues like inconsistent patterns, missing data, and messy text.
   - Applied transformations to derive clean columns for further analysis.
   
2. **DAX (Data Analysis Expressions)**:
   - Created measures to compute key insights such as the highest warranty, top brands based on ratings, and the laptops with the highest discounts.
   - Implemented **DAX** calculations to dynamically handle missing and "Not Available" warranty data.

## Data Cleaning Steps

### 1. Brand Extraction
- **Challenge**: Brand information was embedded within the product name, with no consistent pattern.
- **Solution**: Used Power Query's *Column from Examples* and custom M code to extract brand names reliably.

### 2. RAM Standardization
- **Challenge**: Inconsistent RAM data (e.g., some rows missing GB, others with irrelevant text).
- **Solution**: Used delimiters to extract RAM from the product name and applied M code to standardize the RAM values.

### 3. Processor Cleaning
- **Challenge**: Processor data was messy, with missing or incomplete values.
- **Solution**: Applied Power Query's delimiter functions and M code to clean and update the processor column.

### 4. Warranty Extraction
- **Challenge**: Warranty information was unstructured and inconsistent in the description.
- **Solution**: Used a custom M code function to extract warranty terms from the product description reliably.

### 4. Removed Irrelevant Columns Like Product Image , URL etc

## Visualizations in Power BI

1. **Brand with Highest Warranty**: A visual representation of the brands with the longest warranties.
2. **Brands with Highest Ratings**: Identified top brands based on the sum of ratings and average star ratings.
3. **Top Laptops by Ratings**: Highlighted the top 5 laptops with the highest ratings and average star ratings.
4. **Top Laptops by Discounts**: Showcased the top 5 laptops offering the highest discounts.

## Repository Content

- **Power BI Report**: The `.pbix` file containing the final dashboard with the above insights.
- **M Code Scripts**: Scripts used in Power Query to clean and transform the data.
- **DAX Measures**: Custom DAX measures for key insights and calculations.

## Technologies Used
- **Power BI**
- **Power Query**
- **M Code**
- **DAX**
- **Excel** (for initial data exploration)

## Conclusion
This project demonstrates how to handle and transform unstructured e-commerce data using **Power BI**, **Power Query**, and **DAX**. The process of cleaning messy data, standardizing information, and deriving insights using advanced features of Power BI is a valuable skill set for data professionals working with real-world datasets.

Feel free to explore the project files, and reach out if you have any questions or suggestions!

---

### Connect with me:
- **[LinkedIn](https://www.linkedin.com/in/vikassharmaanalytics)**
- **[GitHub](https://github.com/vikassharma26)**

