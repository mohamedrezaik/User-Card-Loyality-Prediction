# User-Card-Loyalty-Prediction

## Project and Data Description
This project focuses on analyzing a bank card transaction and user (card) loyalty dataset provided by a bank in Brazil. The main goal is to solve data quality issues, perform statistical and regression analysis, and predict a loyalty score for each card id represented in the userscore.csv file.

### Data Files
  - userscore.csv: contains card ids and information about the card itself, including the first month the card was active. It also includes the analysis target, the score, which is a loyalty score calculated by the bank. This file provides three anonymized card categorical features.

  - merchants.csv: provides aggregate information for each merchant id represented in the dataset. This file can be joined with transaction sets to provide additional merchant-level information.

  - historical_transactions.csv and new_merchant_transactions.csv: contain information about each card's transactions. historical_transactions.csv contains up to three months' worth of transactions for every card at any of the provided merchant ids. new_merchant_transactions.csv contains the transactions at new merchants, i.e., those merchant ids that a particular card id has not yet visited, over two months.

### Project Goals
This project aims to accomplish the following:

  - Conduct data exploration to understand the distribution of data, detect outliers, and identify patterns.

  - Perform statistics and hypothesis tests tounderstand the relationships between variables and test hypotheses.

  - Conduct regression analysis to predict the loyalty score for each card id represented in the dataset.

Overall, the analysis performed in this project will help the bank improve its understanding of customer loyalty and inform strategies to increase customer retention.
