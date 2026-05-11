create database loan_data

create table loan_data(
customer_id varchar(50) primary key ,credit_policy int,	purpose varchar,	int_rate float , installment float,	log_annual_inc float,
dti float, fico int,	days_with_cr_line float,	revol_bal int,	revol_util float,	inq_last_6mths int,	delinq_2yrs int,
pub_rec int	,not_fully_paid int
)

copy loan_data(
customer_id	,credit_policy,	purpose,	int_rate,	installment,	log_annual_inc,	dti,	fico,	days_with_cr_line,
revol_bal,revol_util ,inq_last_6mths,	delinq_2yrs,	pub_rec,	not_fully_paid
)
from 'C:\Users\israi\Downloads\loan_data.csv'
delimiter ','
header csv
