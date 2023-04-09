# Lending Club Case Study
> A case study to analyse loan data and give insights on the applicants who are more likely to default on loans.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Provide general information about your project here.
- What is the background of your project?
Project is about to give analytics to the lending club which is our customer based on the loan data set provided.
- What is the business probem that your project is trying to solve?
We want to give insights based on the dataset whether a new applicant should be given a loan and what is the probability of applicant defaulting on loan.
- What is the dataset that is being used?
A loan dataset is provided that contains the data regarding the loan application details.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
In our analysis for the "Charged Off" loan_status category, these category of applications are more likely to default.

<ul>
<li>Applicants whose home ownership status is 'RENT'.</li>
<li>Applicants who took loan for the purpose of 'debt_consolidation'.</li>
<li>Applicants who belong to grade B and subgrade B5.</li>
<li>Applicants who has work experience of 10+ years.</li>
<li>Applicants whose interest rate fall in the range of 13-17%.</li>
<li>Applicants who have less accounts open.</li>
<li>Applicants whose annual income fall in range 31k to 58k.</li>
<li>Applicants whose loan tenure is 36 months.</li>
<li>Applicants whose verifications status is 'Not Verified'</li>
<li>Applicants who inquired 0 times in last 6 months for further loans.</li>
<li>Applicants whose pub_record is 0.</li>
<li>Applicants who took loan in year 2011 and in the month of December.</li>
<li>Applicants whose loan amount is in range 5k-10k.</li>
<li>Applicants whose dti is in range 12-18.</li>
<li>Applicants whose installments is in range 145-274.</li>
</ul>

###Observations in correlating two columns.
These are the following correlations that are more likely to default.

<ul>
<li>Annual income in range 60k-70k and loan purpose is 'home_improvement'.</li>
<li>Annual income in range 60k-70k and home ownership status as 'MORTGAGE'.</li>
<li>Annual income in range 60k-70k and interest rate in range 21%-24%.</li>
<li>Loan amount in range 30k-35k and interest rate in range 15%-17.5%.</li>
<li>Loan amount in range 12k-14k and loan purpose is 'small_business'.</li>
<li>Loan amount in range 12k-14k and home ownership is either 'MORTGAGE' or 'OTHER'.</li>
<li>Loan amount in range 12k-14k and loan amount is greater than 16k.</li>
</ul>


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- numpy
- pandas
- matplotlib
- seaborn

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->


## Contact
Created by [@amanchourasiya] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
