# Big-Data-and-Advanced-Analytics
H-1B Visa Petitions 2011-2016
Abstract

The H1B Visa enables foreign skilled workers to stay in the US for up to six years and apply for permanent residency. Because this visa permits a foreign national to have "dual intent", there is no conflict when an H1B temporary worker applies for a green card. It is important for the U.S. Department of Labor to identify which employers are sending the most number of H1B Visa applications and what is the percentage share of the annual 85,000 visa cap for the employers with most applications. 
At the same time, figure out the most common job title, examine the data science jobs, and their relative wages for which the application is coming in larger frequency, the most popular job and its demand in future. 
It will provide correlation between visa application attributes and the final status outcome. By performing a classification task, which takes in the information about applicants’ prevailing wage, employer name, state the worksite belongs to, occupation code, full-time status and predicts the visa status as ’DENIED’ or ’CERTIFIED’.
This study provides information about the employment gaps within the U.S., which are filled by foreign workers. This gives an idea as to which areas the U.S. government should emphasize to encourage domestic students to develop more local workforce in those job domains for the future. 


Introduction 

This study on the H1B Visa answers some of the questions that could be formed regarding H1B applications in the U.S. H1B Visa applications are increasing year by year and this study helps to identify the jobs that are being filled by the foreign workers. Also, Data Science is a new field since 2010, and this study provides information about the rising demand of the jobs related to the field of data science. 
The source of the data set is the Office of Foreign Labor Certification (OFLC) – United States Department of Labor. 
Some interesting questions that are answered in this study. 
1) What has been the status of the petitioned applications in the time frame.? 
2) Which employers send the most number of H-1B visa applications? 
3) Most common job titles and their relative wages to the Industry standard as well as absolute? 
4) What percentages of the job is full time and what percentage is part-time? 
5) Which are the most common cities where the H1B employee lands in? 
6) How have the Data Science related jobs has performed.
7) The demand of most popular job in the future.

H-1B Visa Data 
The H-1B is an employment-based, non-immigrant visa category for temporary foreign workers in the United States. For a foreign national to apply for H1-B visa, an US employer must offer a job and petition for H-1B visa with the US immigration department. This is the most common visa status applied for and held by international students once they complete college/ higher education (Masters, PhD) and work in a full-time position.
The Office of Foreign Labor Certification (OFLC) generates program data that is useful information about the immigration programs including the H1-B visa. The disclosure data updated annually is available at https://www.foreignlaborcert.doleta.gov/performancedata.cfm
In this project, I will analyze over 3 million records of H-1B petitions in the period 2011-2016.
Source of Data set: https://www.kaggle.com/nsharan/h-1b-visa

Dataset Description
The relevant columns include:
1) EMPLOYER_NAME: Name of employer submitting the H1-B application. Used in comparing salaries and number of applications of various employers.
2) JOB_TITLE: Title of the job using which we can filter specific job positions for e.g., Data Scientist, Data Engineer etc.
3)PREVAILING_WAGE: The prevailing wage for a job position is defined as the average wage paid to similarly employed workers in the requested occupation in intended employment. The prevailing wage is based on the employer’s minimum requirements for the position
4) WORKSITE_CITY, WORKSITE_STATE: The foreign worker’s intended area of employment. We will explore the relationship between prevailing wage for Data Scientist position across different locations.
5) CASE_STATUS: Status associated with the last significant event or decision. Valid values include “Certified,” “Certified-Withdrawn,” Denied,” and “Withdrawn”. This feature will help us analyze what share of the H-1B visa is taken by different employers/ job positions.
Other important columns include Unit of Pay and whether the Job position is a Full-Time position or a Part-Time position.
6) YEAR: 2016 and 2015
7) FULLTIME: ‘Y’ or ‘N’
