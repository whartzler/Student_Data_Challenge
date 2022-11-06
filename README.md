# Student_Data_Challenge

# Overview
Using Jupyter notebooks we collected, prepared, summarized and analyzed student data. 

## Process

### Cleaning the Data
With this student data.csv we removed all NaN and Duplicate values.  The grade column had 'th' and the end of its values,  this was removed and coverted to an int object.

### Summarizing the Data

Summarized all the data to review basic statistics of the data.

### Drilling down into the Data

Using loc & iloc we conducted reviews on different columns so see any possible correlation.  After reviewing the grade 9 column we analyzed basic statistics of the grade.

#### Analysis on Charter and Public Schools. 

Using the groupby function to combine the school types Charter Schools and Public Schools we analyzed math_scores and the budget for each school type.  Also we reviewed the total amount of students per school.
