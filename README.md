# BMI6016A1

Data Wrangling Assignment

In this assignment, we are interested in exploring the effects of the exposome on pediatric
asthma. Towards that we will assess and wrangle the provide data by answering the following
questions. You will use the codebook, covariates, exposome and phenotype files. Submit your
responses in a PDF file including your code and results. You can use Python or R. Do ask for
help and if you have any questions.

1. Using the covariates dataset, group the data by sex "e3_sex_None". Which
gender has the highest weight "hs_c_weight_None '' and what is its
corresponding mean value?

2. Create a dataframe called “phenotype” using the phenotype dataset and answer the
following questions:

a. Count the number of missing values per column in the above dataframe.

b. Extract and Print all individuals (IDs) from the dataframe what have a Body
mass index categories at 6-11 years old - WHO reference of Overweight or 
Obese. Refer the Codebook file to find the field and values.

c. Identify any records (IDs) that are duplicative in the records you extracted in
Step b.

Part 2

Data Wrangling Assignment Part 2
Submit your responses in a PDF file including your code and results. You can use Python or R. 
Do ask for help and if you have any questions.

1. Create a dataframe called ‘exposome’ using the exposome dataset and answer the
following questions. Refer the Codebook file to find the field and values. You will 
use the datasets and dataframe from Part 1 of this assignment.

a. Add a new column to the dataframe exposome called ‘cotinine_combination’
which combines all possible values of cotinine in mother
(hs_cotinine_mcat_None) and cotinine in child (hs_cotinine_cdich_None). Create
values of your choice in this new field and provide a count for each of these
combined values. (15 Points)

b. Using the exposome and phenotype dataframes, plot ‘cotinine_combination’
and the patients having doctor diagnosed asthma. 15 Points)
2. Please use the file ‘NO2_2020_California’ to answer the following questions. You can 
use Python, R, or other programming languages that you are familiar with:
a. How many unique county names are in this file? After checking how many 
unique counties in this file, please choose a reasonable plot to show the 
distribution of counties. You can use either matplotlib or seaborn. (15 Points)
3. Please use the file ‘NO2_2020_California’ to answer the following questions:
a. Find the geo-coordinates for ‘Martin Luther King High School’ with address 
‘9301 Wood Rd, Riverside, CA 92508’. (5 Points)
b. Find the nearest monitor by distance in the file ‘NO2_2020_California’ to the 
above school. (10 Points)
c. Next, find the monthly average, monthly minimum and monthly maximum for 
NO2 for this monitor for the year 2020. (15 Points)
d. Plot the monthly average, monthly minimum and monthly maximum NO2 on a 
graph using matplotlib or seaborn. (15 Points