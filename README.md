# Predicting Whether The Customer Will Subscribe To Term Deposit
### Data Description:
The marketing campaigns were based on phone calls. Often, more than one contact to the same client was required, in order to access if the product (bank term deposit) would be (‘yes’) or not (‘no’) subscribed.

### Attribute Information:
* age (numeric)

* job : type of job (categorical: ‘admin.’,’bluecollar’,’entrepreneur’,’housemaid’,’management’,’retired’,’selfemployed’,’services’,’student’,’technician’,’unemployed’,’unknown’)

* marital : marital status (categorical: ‘divorced’,’married’,’single’,’unknown’; note: ‘divorced’ means divorced or widowed)

* education (categorical:‘basic.4y’,’basic.6y’,’basic.9y’,’high.school’,’illiterate’,’professional.course’,’university.degree’,’unknown’)

* default: has credit in default? (categorical: ‘no’,’yes’,’unknown’)

* balance: average yearly balance, in euros (numeric)

* housing: has housing loan? (categorical: ‘no’,’yes’,’unknown’)

* loan: has personal loan? (categorical: ‘no’,’yes’,’unknown’)

* contact: contact communication type (categorical: ‘cellular’,’telephone’)

* day: last contact day of the month (numeric 1 -31)

* month: last contact month of year (categorical: ‘jan’, ‘feb’, ‘mar’, …, ‘nov’, ‘dec’)

* duration: last contact duration, in seconds (numeric). Important note: this attribute highly affects the output target (e.g., if duration=0 then y=’no’). Yet,the duration is not known before a call is performed. Also, after the end of the call y is obviously known. Thus, this input should only be included for benchmark purposes and should be discarded if the intention is to have a realistic predictive model.

* campaign: number of contacts performed during this campaign and for this client (numeric, includes last contact)

* pdays: number of days that passed by after the client was last contacted from a previous campaign (numeric; 999 means client was not previously contacted)

* previous: number of contacts performed before this campaign and for this client (numeric)

* poutcome: outcome of the previous marketing campaign (categorical:‘failure’,’nonexistent’,’success’)

* target: has the client subscribed a term deposit? (binary: “yes”,”no”)

### Objective:
The classification goal is to predict if the client will subscribe (yes/no) a term deposit (variable y).
