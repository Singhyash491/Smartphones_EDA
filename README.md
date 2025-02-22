# 📊 Smartphone EDA  

## 📝 Overview  
This project performs **Exploratory Data Analysis (EDA)** on a dataset of smartphones, analyzing various features such as price, brand, processor, camera specifications, and more. The goal is to uncover patterns and relationships between these features and key factors like price and customer ratings.  

## ❓ Problem Statement  
With the increasing variety of smartphones in the market, customers often struggle to understand **what factors contribute to a smartphone's price** and **how different features impact customer ratings**. This analysis aims to provide insights into the **key features affecting smartphone pricing and consumer preferences**.  

## 🔍 Solution Approach  
1. **Data Preprocessing & Cleaning**  
   - Handled missing values using **KNN Imputer**.  
   - Removed unnecessary columns and ensured consistency in data types.  

2. **Exploratory Data Analysis (EDA)**  
   - **Brand Popularity**: Identified top smartphone brands.  
   - **Price Analysis**: Distribution of smartphone prices and outliers.  
   - **Feature Analysis**: Relationship between features like **5G, processor brand, screen size**, and price.  
   - **Correlation Study**: Used scatter plots, heatmaps, and box plots to find **feature-price relationships**.  

3. **Data Visualization**  
   - Bar charts, pie charts, histograms, and scatter plots were used to **interpret insights visually**.

## 🔑 Key Findings  
- **Price Distribution**: Majority of smartphones fall under ₹50,000, but some high-end flagships go beyond ₹2,50,000.  
- **Feature Impact on Price**:  
  - **5G, NFC, and IR Blaster** are mostly found in **expensive smartphones**.  
  - **Processor brand & number of cores** impact pricing significantly.  
  - **Screen size & processor speed** have a moderate positive correlation with price.  
- **Customer Ratings**:  
  - Most smartphones are rated between **3.5 and 4.5**, indicating general satisfaction.  
  - **Price and rating have a weak correlation**, suggesting that expensive phones don’t always receive the highest ratings.  

## 🛠️ Libraries & Tools Used  
- **Python** (pandas, numpy, matplotlib, seaborn, sklearn)  
- **Jupyter Notebook**  

## ⚙️ How It Works  
1. **Load the dataset** and check for missing/duplicate values.  
2. **Visualize key features** (brands, prices, rating distribution, 5G availability, etc.).  
3. **Analyze relationships** between smartphone features and pricing.  
4. **Identify patterns** in consumer ratings and smartphone specifications.  

## 🚀 How to Run  
1. Clone the repository or download the notebook.  
2. Install dependencies using:  
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
3. Run the Jupyter Notebook or Google Colab.
4. Load the dataset (smartphone.csv).
5. Execute the cells to visualize and analyze the data.
