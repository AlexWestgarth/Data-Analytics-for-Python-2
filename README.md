# Data-Analytics-for-Python 2
A completed data analysis of movie sets as part of a university assignment
The business situation is entirely fictional and uses real world data.
This assignment is an extension of the first assignment, using the same data with slightly adjusted business problem statements and a higher focus on visualisations

# Purpose
To demonstrate data analytical skills in python, namely:
 - Loading data
 - Data inspection
 - Data manipulation
 - Data analysis
 - Data visualisation
 
 Additionally the use of business problem statement understanding and transformation into a data-driven report.

# Introduction
A company that specialises in French-language movie streaming wishes to gain data-driven insights on which business decisions should be made regarding their platform.
To accomplish this, a dataset containing 15000 entries of movies and various details about them was utilised.
# Method
Using the python language via the Jupyter Notebook interface the entire data analytics process excluding data discovery is completed.

The data is first loaded into pandas dataframe objects and inspected.

As there are two datasets, they are merged into one singular dataset via a left join.

The data is then cleaned according to the business requirements, namely the use of rating, country and language to drop NA values.

The data is also modified to include a more useful variant of the scoring metrics, the primary business target metric.

Adjustments are made to the genre data column to allow greater analytical insight, namely by breaking down the original string into list format.

The data is then analyised with respect to the business problem requirements.

The analyised data is then transformed into visualisations for easy data-driven report writing.
