create database loan_data

create table loan_data(
customer_id varchar(50) primary key ,credit_policy int,	purpose varchar,	int_rate float , installment float,	log_annual_inc float,
dti int, fico int,	days_with_cr_line float,	revol_bal int,	revol_util float,	inq_last_6mths int,	delinq_2yrs int,
pub_rec int	,not_fully_paid int
)
