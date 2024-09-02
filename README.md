# Capstone-Project_1-ML
Project: Customer Targeting: Predicting Term Deposit Subscriptions in Bank Marketing

Business Objective:

The goal is to develop a predictive model to classify whether a client will subscribe to a term deposit based on demographic, socio-economic, and campaign-related factors.

The data file contains 41118 customers information and 21 columns 

Variable Descriptions
1.	age: (Numeric) Age of the client.
2.	job: (Categorical) Type of job (e.g., admin, technician, blue-collar, etc.).
3.	marital: (Categorical) Marital status (e.g., married, single, divorced).
4.	education: (Categorical) Education level of the client (e.g., primary, secondary, tertiary, unknown).
5.	default: (Binary) Whether the client has credit in default (yes/no).
6.	housing: (Binary) Whether the client has a housing loan (yes/no).
7.	loan: (Binary) Whether the client has a personal loan (yes/no).
8.	contact: (Categorical) Contact communication type (e.g., cellular, telephone).
9.	month: (Categorical) Last contact month of the year (e.g., January, February).
10.	day_of_week: (Categorical) Last contact day of the week (e.g., Monday, Tuesday).
11.	duration: (Numeric) Last contact duration, in seconds. Note: This feature is highly predictive but should be handled carefully in predictive modelling.
12.	campaign: (Numeric) Number of contacts performed during this campaign and for this client (includes the last contact).
13.	pdays: (Numeric) Number of days since the client was last contacted from a previous campaign. -1 means the client was not previously contacted.
14.	previous: (Numeric) Number of contacts performed before this campaign and for this client.
15.	poutcome: (Categorical) Outcome of the previous marketing campaign (e.g., success, failure, unknown, non-existent).
16.	emp_var_rate: (Numeric) Employment variation rate (quarterly indicator).
17.	cons_price_idx: (Numeric) Consumer price index (monthly indicator).
18.	cons_conf_idx: (Numeric) Consumer confidence index (monthly indicator).
19.	euribor3m: (Numeric) Euribor 3-month rate.
20.	nr_employed: (Numeric) Number of employees (quarterly indicator).
21.	y: (Binary) Target variable indicating whether the client subscribed to a term deposit (yes/no).
Problem Statement: Using the provided data, develop a classification model that predicts whether a client will subscribe to a term deposit (yes/no) based on personal characteristics, contact details, and economic indicators. This model can help the bank improve its marketing strategy by identifying the characteristics of clients who are likely to respond positively to marketing campaigns, thereby enhancing campaign effectiveness and customer acquisition.

Acceptance Criterion: 
Need to deploy the end results using Flask /Streamlit.etc.

