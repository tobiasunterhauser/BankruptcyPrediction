# Bankruptcy Prediction Taiwan Economic Journal - Classification 


### Rational including the open issues and research questions 

The goal of this study was
to identify the most effective classification model for predicting bankruptcy using data from the
Taiwan Economic Journal. Bankruptcy prediction is an important field in finance. This prediction
can help stakeholders like employees, shareholders and customers make decisions to avoid potential
losses when there is a high risk of financial distress. This can be very helpful as for the single
stakeholder it might be too difficult to analyze all the data at hand and interpret it by himself.
To reach this goal, a dataset from the Taiwan Economic Journal containing financial data for a large
number of publicly traded companies was analyzed. I selected a range of financial indicators that
have been shown to be predictive of bankruptcy and have the highest correlation with the target
class, including profitability, liquidity, leverage, and solvency ratios. In the next step different
machine learning algorithms were trained on to the data and their predictions were compared by
using different performance metrics. The best-performing models were further tuned in order to
obtain a model with the most accurate prediction for our use case.

Description of the data-set The dataset was taken from Kaggle. The data was collected from
the Taiwan Economic Journal and covers the time period from 1999 - 2009. Whether a company
was bankrupt or not was defined based on the business regulations of the Taiwan Stock Exchange.
It contains 95 Financial metrics and the target class which states whether a company is bankrupt or
not. Having some domain knowledge I know that some of the metrics are going to be redundant as
some are calculated similarly and therefore will have a high correlation to each other. In addition
not in every case of bankruptcy there is a direct link to the financial metrics as there may be
also other external influences impacting the company. Nonetheless based on financial metrics the
health of a company can be determined and classified in order to make a good enough prediction.
A challange is going to be the high class imbalance in the target class as we will see during the
data exploration.