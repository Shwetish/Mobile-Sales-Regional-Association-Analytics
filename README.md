# Mobile-Sales-Regional-Association-Analytics
Evaluates historical regional sales data for mobile phones using association rules to provide the marketing team with data-driven insights for upcoming new product launches.

# 📱 Mobile Sales: Regional Association Analytics & New Product Launch Suite

## 1. Business Problem

### 1.1. What is the business objective?
* **New Product Launch Strategy:** Help the marketing team analyze historical regional sales data for previous mobile phone models before launching three brand-new smartphone variants.
* **Association Mining:** Apply association rule mining to uncover regional buying patterns, cross-device preferences, and feature combinations that drive regional purchasing decisions.

### 1.2. Are there any constraints?
* **Regional Disparities:** Managing variations in customer preferences and purchasing power across different geographic regions.
* **Threshold Tuning:** Selecting balanced support and confidence thresholds to isolate robust regional sales trends without getting skewed by low-volume regional outliers.

---

## 2. Data Dictionary (`myphonedata.csv`)

| Feature Name | Data Type | Description |
| :--- | :--- | :--- |
| **Transaction / Order ID** | Integer / String | Unique identifier for each smartphone sale or purchase record. |
| **Region / Location** | Categorical | Geographic region or market where the phone model was sold. |
| **Phone Models / Features** | Categorical / Binary | Identifiers for the specific smartphone models and accessory options purchased. |

---

## 3. Data Pre-processing

### 3.1. Data Cleaning & Feature Engineering
* **Data Transformation:** Processed multi-region sales data into structured boolean or one-hot encoded matrices grouped by regional transactions.
* **Data Sanitization:** Handled missing sales entries and normalized region and model names for consistent analysis.

---

## 4. Model Building

### 4.1. Application of Apriori Algorithm
* Implemented the Apriori algorithm via Python libraries (e.g., `mlxtend`) to identify frequent itemsets across different geographic regional datasets.
* Evaluated rules using **Confidence** and **Lift** to determine high-probability purchasing patterns for target regions.

### 4.2. Frequent Itemsets & Rule Visualization
* Generated frequent itemsets and visualized association metrics with scatter plots and regional distribution charts to assist the marketing team.

### 4.3. Work on Codes
* The complete source code implementation is stored in the `My_phone_data.py` file.

---

## 5. Deployment

### 5.1. Deploy Solutions
* The regional association rules can be compiled into a market intelligence dashboard or decision-support report for regional marketing heads to optimize targeted ad placements.

---

## 6. Business Impact & Benefits
* **Targeted Launch Campaigns:** Enables the marketing team to move away from blanket traditional campaigns and execute region-specific promotional strategies for the three new phone models.
* **Maximized ROI:** Aligns marketing budgets with proven regional buying behaviors, improving conversion rates and sales velocity upon launch.
