# **Market Basket Analysis for Retail Transactions**

## **Overview**
This project focuses on performing market basket analysis on transactional retail data to identify products that are frequently purchased together. The insights from this analysis can be used to optimize product placement, create promotional bundles, and improve cross-selling strategies.

### **Programming Language**
Python

### **Skills Showcased**
This project demonstrates proficiency in several key areas:

#### **1. Data Preparation & Feature Engineering**
Classification of categorical variables as ordinal or nominal, followed by appropriate encoding techniques (ordinal encoding and one-hot encoding). Transactionalized order data by grouping products by OrderID and transforming it into a basket matrix using TransactionEncoder.

#### **2. Market Basket Analysis (Apriori Algorithm)**
Applied the Apriori algorithm to identify frequent itemsets and generated association rules using support, confidence, and lift metrics. Filtered and ranked rules to identify the strongest product associations.

#### **3. Data Export & Reproducibility**
Exported the transactionalized dataset using to_csv() to ensure reproducibility and enable downstream analysis.

#### **4. Business Insight & Interpretation**
Interpreted association rules to identify highly predictable product bundles and explained statistical metrics such as support, confidence, and lift. Translated technical results into actionable business recommendations.

#### **5. Retail Strategy Recommendations**
Provided recommendations for product bundling, cross-sell recommendation systems, and store or website product placement to improve marketing effectiveness and increase average order value.
