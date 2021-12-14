# Sport Data Analysis 
## Objective:
We are a part of XYZ Co Pvt Ltd company who is in the business of organizing the sports events at international level. Countries nominate sportsmen from different departments and our team has been given the responsibility to systematize the membership roster and generate different reports as per business requirements.

## Dataset:
We are given data that are present in 3 sheets with the name -
1)Sportsmen:It contains information about sportsmen member id,full name,birthdate,gender,country code,country name,email,salary,blood group,sport location ,weight.....<br/>
2)Sport:It contains information about type of sport and sport location.<br/>
3)Location:It contains information about country code,country name and language of sportsmen.

## Tools Used:
Excel

## Summary:
We did this project in three stages: 
1) Data Cleaning:
We performed data cleansing by using excel functions.for example we created a new column with the name of full name from 3 existing columns prefix,firstname and          lastname,got the COUNTRY NAME to which these sportsmen belong to by making use of location sheet,Populated the LANGUAGE spoken by the sportsmen by making use of location sheet,Generated the EMAIL ADDRESS for those members, who speak English, in the prescribed format : lastname.firstname@xyz.org (Note: All lowercase) and for all other members, format was the lastname.firstname@xyz.com (Note: All lowercase)
Then we performed some data formatting. Ex-Formatted the BIRTHDATE as dd mmm' yyyy (Prescribed format example: 09 May' 1986),Formatted the SALARY to show the data in thousands. If SALARY is less than 100,000 then display data with 2 decimal places else display data with one decimal place. In both cases units should be thousands (k)

2) Data Analysis: We analyzed the data by using pivot table and excel functions.

3) Generate Report: Then we created a report as per business requirement.


