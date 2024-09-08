# [BCG - Data Science Project](https://www.theforage.com/simulations/bcg/data-science-ccdz)

---

## Project Background
- PowerCo - a major gas and electricity utility that supplies to small and medium sized enterprises.  
- The energy market has had a lot of change in recent years and there are more options than ever for customers to choose from.  
- PowerCo are concerned about their customers leaving for better offers from other energy providers. When a customer leaves to use another service provider, which is called churn.  
- This is becoming a big issue for PowerCo and they have engaged BCG to help diagnose the reason why their customers are churning.

---

## Procedure



### Step 1. [Exploratory Data Analysis(EDA)](DataAnalysis/EDA)
Here are 3 data sets:
1. [Historical customer data](Datasets/client_data.csv): Customer data such as usage, sign up date, forecasted usage etc.
2. [Historical pricing data](Datasets/price_data.csv): variable and fixed pricing data etc.
3. Churn indicator: whether each customer has churned or not.

Analyze the following using Python:
1. The data types of each column.
2. Descriptive statistics of the dataset.
3. Distributions of columns.



### Step 2. [Feature Engineering](DataAnalysis/Feature_Engineering)



### Step 3. [Predict Churn](DataAnalysis/Modeling)
Use Random Forest Regression Model to predict churn rate



### Step 4. Data Interpretation
**Churn is indeed high in the SME division**    

  • 9.7% across 14606 customers

**Predictive model is able to predict churn but the main driver is not customer price sensitivity**     

  • Yearly consumption, forecasted consumption and net margin are the 3 largest drivers

**Discount strategy of 20% is effective but only if targeted appropriately**     

  • Offer discount to only to high-value customers with high churn probability
