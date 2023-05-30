# User-Card-Loyality-Prediction
## Project And Data Describtion:
  - The data is a bank card transaction and user (card) loyalty analysis dataset
provided by a bank in Brazil. This project aims to solve some problems, i.e., data quality analysis, statistical analysis, and regression
analysis given the dataset. The overall purpose of the analysis is to predict a
loyalty score for each card id represented in userscore.csv.

  - userscore.csv contain card ids and information about the card itself - the
first month the card was active. It also contains the predict/analysis target,
i.e., score, which is a score calculated by the bank, indicating the loyalty of
each card owner. Three features are provided, all of which are anonymized card
categorical features.

  - merchants.csv contains aggregate information for each merchant id represented
in the data set. merchants can be joined with the transaction sets to
provide additional merchant-level information.

  - The historical transactions.csv and new merchant transactions.csv files contain
information about each card’s transactions. historical transactions.csv contains
up to 3 months’ worth of transactions for every card at any of the provided
merchant ids. new merchant transactions.csv contains the transactions at new
merchants (merchant ids that this particular card id has not yet visited) over
two months.
  - historical transactions.csv and new merchant transactions.csv are designed
to be joined with userscore.csv and merchants.csv. They contain information
about transactions for each card, as described above.

## Some Cases Will Be Covered:
  - Data Exploration.
  - Statistics and Hypothesis Test.
  - Regression Analysis.
