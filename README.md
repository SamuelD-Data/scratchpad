# Credit Card Sample Data V3

### Columns From Source Data

For explanations pertaining to the columns that were not added manually, visit the source page.

https://www.kaggle.com/sakshigoyal7/credit-card-customers

### New Columns

See below for explanations regarding the new columns that were added manually.

Note that 'q1', 'q2', and 'q3' in the column names of the actual dataset denote which quarter a particular column is referring to.

__CLIENTNUM__  
Unique identifier for each customer

__marketed_content__ 
Indicates the type of marketing content that was sent to the customer during the corresponding quarter

__fraud__
Indicates if fraud was detect during the corresponding quarter

__q1_cred_req_dec__
Indicates if customer was declined a credit increase request during the corresponding quarter

__q1_int_abv_100__
Indicates if customers average interest charge was over $100 during the corresponding quarter

__q1_call_escalation__
Indicates if a call the customer made was escalated to a supervisor during the corresponding quarter

__q1_low_survey_score__ 
Indicates if the customer gave a low customer service survery score during the corresponding quarter

__counter__
All rows have value of 1. Can be used in tableau calculations.

__exit_survey__
Message from customer in exit survey after closing account. 'NA' indicates customer has not closed account and thus did not do survey.

__churned__
0 = Customer has not churned
1 = Customer has churned

__churn_reason__
Reason for customer churning. 'NA' indicates customer has not churned.
