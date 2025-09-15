# Customer-Segmentation-for-E-commerce

## Project Overview

This project focuses on analyzing and segmenting customer data from an online retail store. The goal is to identify distinct customer groups based on their purchasing behavior using unsupervised learning (K-Means clustering) and then build predictive models using supervised learning (Random Forest and Logistic Regression) to classify new customers into these segments. This segmentation can inform targeted marketing strategies, customer relationship management, and business decision-making.

## Project Goals

*   Load and preprocess the raw online retail transaction data.
*   Perform exploratory data analysis (EDA) to understand the data distribution and key trends.
*   Prepare customer-level data with relevant features for segmentation.
*   Determine the optimal number of customer segments using the Elbow method.
*   Apply K-Means clustering to group customers into distinct segments.
*   Analyze and interpret the characteristics of each customer segment.
*   Prepare the data for classification by splitting into training and testing sets.
*   Train Random Forest and Logistic Regression models to predict customer segment membership.
*   Evaluate the performance of the classification models.
*   Provide insights into the identified customer segments.

## Dataset

The dataset used in this project is the **"Online Retail"** dataset, available from the UCI Machine Learning Repository. It contains transactional data from a UK-based online retail store.

*   **File:** `Online_Retail(dataset).xlsx`

**Key Columns:**
*   `InvoiceNo`: Invoice number. Nominal. A 6-digit integral number uniquely assigned to each transaction. If this code starts with the letter 'c', it indicates a cancellation.
*   `StockCode`: Product (item) code. Nominal. A 5-digit integral number uniquely assigned to each distinct product.
*   `Description`: Product (item) name. Nominal.
*   `Quantity`: The quantity of each item per transaction. Numeric.
*   `InvoiceDate`: Invoice date and time. Numeric. The day and time when each transaction was generated.
*   `UnitPrice`: Unit price. Numeric. Product price per unit in sterling (£).
*   `CustomerID`: Customer number. Nominal. A 5-digit integral number uniquely assigned to each customer.
*   `Country`: Country name. Nominal. Name of the country where each customer resides.

## Technical Stack

*   **Language:** Python
*   **Libraries:**
    *   `pandas`: For data manipulation and analysis.
    *   `numpy`: For numerical operations.
    *   `matplotlib`: For data visualization.
    *   `seaborn`: For enhanced statistical data visualization.
    *   `sklearn` (Scikit-learn): For machine learning algorithms (K-Means, RandomForestClassifier, LogisticRegression) and preprocessing tools (StandardScaler, train_test_split).
    *   `scipy`: For scientific and technical computing (specifically used for zscore).
    *   `openpyxl`: To read `.xlsx` files with pandas.
