# 🛍️ Online Shopping Session Analysis  

This project explores customer behavior during the busiest shopping months, **November** and **December**. Using a dataset of online shopping sessions, we analyze purchase rates, correlations between page durations, and the likelihood of sales based on boosted campaign efforts.  

## 🗂️ Project Overview  
The marketing team requested insights into:  
1. **📊 Purchase Rates**: Calculating purchase rates for returning and new customers.  
2. **🔗 Strongest Correlation**: Finding the strongest correlation in time spent on different page types.  
3. **🎯 Sales Likelihood**: Estimating the likelihood of achieving at least 100 sales from 500 sessions with a boosted campaign.  

## 🔧 Tools & Technologies  
- **Python 🐍**  
- **pandas 📋**  
- **NumPy ➕**  
- **Matplotlib 📈**  
- **SciPy Stats 📊**  

## 📁 Dataset Description  
The dataset includes:  
- `SessionID`: Unique identifier for each session.  
- `CustomerType`: Whether the customer is a **Returning** or **New** visitor.  
- `Month`: Session month.  
- `Purchase`: Whether the session resulted in a purchase.  
- `Administrative_Duration`, `Informational_Duration`, `ProductRelated_Duration`: Time spent on respective pages.  

## 🚀 Key Features  
1. **Purchase Rates Calculation**  
   - Purchase rates for both customer types during November and December are stored in the dictionary:  
   ```python  
   purchase_rates = {"Returning_Customer": 0.254, "New_Customer": 0.276}  
