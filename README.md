# Exploratory-Data-Analysis
**1. Introduction**

   Brief overview:
   
  The Online Retail dataset is studied and Exploratory data analysis is done on it using Python programming language with the help of Google-Collaboratory platform.
  
  Objective of the analysis:
  
  My objective is to understand insights of the Online Retail Dataset to improve its Sales by knowing its sales trends.
  
  Description of the dataset:
  
  The dataset consists of eight columns including the description of the items, Country, unit price, customer ID, quantity, Stock code, invoice ID, and invoice date. 

**2. Data Collection and Preprocessing**
  
  Source of the dataset
  
  The data set is provided on Coursera learning platform (Link in references).
   
  Columns present in the dataset
  
  1. InvoiceNo
  2. StockCode
  3. Description
  4. Quantity
  5. InvoiceDate
  6. UnitPrice
  7. CustomerID
  8. Country 
    
  Data cleaning steps taken 
  
  1.	**Removing duplicates**:
  
  I have used the drop_duplicated() method to remove all the duplicates present. 
  
  To verify the duplicated rows are deleted, I have used .shape attribute. Initially it shows the shape as (541909, 8) and after the dropping is done, it gives the result as (536641, 8).

  2.	**Removing nulls:**
  
  .dropna() method is used to drop all the nulls present in the dataset. 
  
  And to verify this, I used .isnull().sum(). This gives us the number of nulls present in each column.

3. **Exploratory Data Analysis (EDA)**

  **3.1 Descriptive Statistics**
  
  •	Summary statistics of key features.
  
  Quantity      =    9.552250

  UnitPrice    =    4.611114
  
  As we can see, the average items sold is 9.5 and the average unit price for each item is 4.6.

  **3.2 Univariate Analysis**
  
  **•	Histogram:** 
  
  ![Untitled](https://github.com/priyankaa370/Exploratory-Data-Analysis-/assets/81320366/8b79985f-1a12-4a27-8a3f-a3b393bf7e4d)

  o	Here, I have visualized the number of sold items by date using a Histogram. We have used histogram because it refers to the frequency of occurrence of a variable (here items) in a given interval and hence, to understand the number of items sold, a histogram justifies perfectly.
 
  **3.3 Bivariate Analysis**
  
  **•	Scatter plot:**
  
  ![Untitled](https://github.com/priyankaa370/Exploratory-Data-Analysis-/assets/81320366/64ec8c34-dfde-428d-ab00-2c6ab0853bef)

  I created a scatter plot indicating the relationship between number of products sold and the countries. 
 
  **3.4 Correlation Analysis**

  •	Correlation matrix and heatmap visualizations

  ![Untitled](https://github.com/priyankaa370/Exploratory-Data-Analysis-/assets/81320366/a29c876a-034d-4f46-ab63-f8ac8120bb4f)
  
 
  •	Insights derived from correlation analysis
  
  From the above heatmap, we can see that as the unit price increases, the quantity sold decreases since it has negative correlation.

  **5. Conclusion**
  
  •	In this Exploratory data analysis, I have used pandas, matplotlib and seaborn to understand the insights of the online retail data. Further the data can be used for the analysis to improve the marketing strategy by understanding patterns.

  **6. References**

  •	mailto:https://www.kaggle.com/code/imoore/intro-to-exploratory-data-analysis-eda-in-python
  
  •	mailto:https://www.coursera.org/learn
