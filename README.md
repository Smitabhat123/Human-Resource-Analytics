# Human-Resource-Analytics

A data-driven approach, that can illuminate the major causes of attrition, and new policies, along with training programs and can help to mitigate the various problems. For example, data might show that high-aspiration employees are not challenged or employees are frustrated with a certain management style. Human resources analysis will reveal these issues. 

## Data Set:

employee_id : Unique Identifier 
department : Sales & Marketing, Operation, Technology, Procurement, Finance, HR
region : 34 different regions
education : Master's & above, Bachelors, Below Secondary
gender : Male/Female
recruitment_channel : sourcing,other,referred.
no_of_trainings 
age 
previous_year_rating   
length_of_service          
KPIs_met >80%             
awards_won?               
avg_training_score        
is_promoted : Response


* Testing Set 20% of the data

### Random Forest : 

* Accuracy_score: 93.50% on test dataset
* precision_score: 74.02% on test dataset
* recall_score: 33.26% on test dataset
* f1_score: 45.90% on test dataset

### KNN :

* Accuracy_score: 92.60% on test dataset
* precision_score: 90.76% on test dataset
* recall_score: 11.89% on test dataset
* f1_score: 21.03% on test dataset

### SVC :

* Accuracy_score: 93.50% on test dataset
* precision_score: 74.02% on test dataset
* recall_score: 33.26% on test dataset
* f1_score: 45.90% on test dataset

### XGBoost :

* Accuracy_score: 93.19% on test dataset
* precision_score: 63.11% on test dataset
* recall_score: 42.95% on test dataset
* f1_score: 51.11% on test dataset
