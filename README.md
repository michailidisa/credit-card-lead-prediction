# credit-card-lead-prediction
CREDIT CARD LEAD PREDICTION

The main aim of our project was to find out customers that would show higher intent towards a recommended credit card or not.

1. Having a predefined set of customers that are eligible for taking these credit cards, we had to deal with a classification problem.
2. This way the bank would be able to better allocate its marketing efforts, leading in more efficient results.


## Key Conclusions

1. If we were about to choose for a well defined model, based on key metrics (F1 - Score & Cohen’s Kapa), we would most probably choose the Gradient Boosted Trees Algorithm, after applying oversampling (F1: 68,5%, Cohen’s: 58,3%).
2. It is indeed a quite efficient algorithm even when we check our results using the KPIs (Net Profit: 834.000)
3. But, taking into account the main objective of all the companies, which is the profit, we end-up selecting the Logistic Regression after applying under-sampling, which offers higher net profit (Net Profit: 1.061.000)


The dataset was obtained through Kaggle (https://www.kaggle.com/code/ankitabanerji/credit-card-lead-prediction-eda/data?select=train.csv) and the analysis was made using the KNIME Software.
