# Credit Card Sample Data V3

### Columns From Source Data

For explanations pertaining to the columns that were not added manually, visit the source page.

https://www.kaggle.com/sakshigoyal7/credit-card-customers

### New Columns

See below for explanations regarding the new columns that were added manually.

__above_avg_int__
0 = Customer's average interest fees were average or below average 
1 = Customer's average interest fees were above average

__low_avg_service_score__
0 = Customer's average customer service survey scores were average or above average 
1 = Customer's average customer service survey scores were below average

__low_avg_online_score__
0 = Customer's average online service survey scores were average or above average 
1 = Customer's average online service survey scores were below average

__fraud_in_history__
0 = Customer had no history of fraud on account
1 = Customer had history of fraud on account

__annual_fee__
0 = Customer paid no annual fee
1 = Customer paid annual fee

__counter__
All rows have value of 1. Can be used in tableau calculations.

__exit_survey__
Message from customer in exit survey after closing account. 'NA' indicates customer has not closed account and thus did not do survey.

__churned__
0 = Customer has not churned
1 = Customer has churned

__churn_year__
Year that the customer churned. Value of 2099 indicates customer has not yet churned.

__churn_reason__
Reason for customer churning. 'NA' indicates customer has not churned.
