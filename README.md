# Frequency-table-and-chi-square

Frequency tables (also known as crosstabs) in pandas using the  pd.crosstab() function. The function takes one or more array-like objects as indexes or columns and 
then constructs a new DataFrame of variable counts based on the supplied arrays

One of the most useful aspects of frequency tables is that they allow you to extract the proportion of the data that belongs to each category. 
With a one-way table, you can do this by dividing each table value by the total number of records in the table

Two way frequency tables 
 
Two-way frequency tables, also called contingency tables, are tables of counts with two dimensions where each dimension is a different variable.
Two-way tables can give you insight into the relationship between two variables. 
To create a two way table, pass two variables to the pd.crosstab() function instead of one.
