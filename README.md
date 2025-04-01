# 3,4 Assignment(Big Data Exploration, ML)

### **1. Data Exploration**
- We analyzed the dataset to understand its structure.
- We counted rows and columns to determine the size of the dataset.
- We checked the data types in each column (e.g., numbers or text).
- We identified missing values and duplicate rows in the data.
- We used descriptive statistics (e.g., minimum, maximum, average) to summarize columns like `Age` and `Purchase_Amount`.

### **2. Cleaning Data**
- **Fixed Missing Values**:
  - We replaced missing numbers (e.g., `Purchase_Amount`) with the average value.
  - We replaced missing text data (e.g., `Country`) with the most common value.
- **Removed Duplicates**:
  - We deleted repeated rows so every transaction was unique.

### **3. Visualizations**
We created charts to find and explain trends:
- **Sales by Country (Bar Chart)**:
  - We showed which countries had the highest total sales.
- **Most Popular Products (Bar Chart)**:
  - We visualized which product categories customers purchased the most.
- **Top Payment Methods (Pie Chart)**:
  - We displayed the share of payment methods, such as Credit Card and PayPal.


### **4. Outliers and Anomalies**
- **Outliers**:
  - We identified extreme values in `Purchase_Amount`, such as unusually high or low amounts compared to others.
- **Anomalies**:
  - We checked for incorrect or unknown values in columns like `Country` and `Payment_Method`.
