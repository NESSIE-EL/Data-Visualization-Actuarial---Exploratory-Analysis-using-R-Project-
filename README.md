“Hello, we entered the dental insurance market last year and we have the dental claims data. We
want you to visualize and explore the data to provide us some insights. We can’t wait to hear
from you. Thanks!” – Chief Actuary

## Task 1) 

Read in the DentalClaims.csv file into R. Name the resulting dataframe, Dental.
Convert the columns (ID, Tier, Procedure, Occupation, Provider, Claim) into factor columns, not
integer. 
Hint: use factor()

## Task 2) 

Create various histograms of the Dental dataset.
A. Histogram of the variable Claim where the stat=”count”
B. Histogram of the variable Claim by Gender where the stat=”count” . 
Consider using facets. 
What insight can you provide by looking at males vs. females?

## Task 3) 
Visualize the people who were insured for dental and had a dental claim (Claim ==1)

A. Create a subset of the dataset Dental where Claim == 1. Call this dataset DentalClaims.

B. Create a density plot of the variable Age using the dataset DentalClaims

C. Create a density plot of the variable Paid using the dataset DentalClaims

## Task 4) 

Analyze how much the dental providers charge.

A. 
Create a boxplot of the variable Provider (x-axis) and Paid (y-axis) using the dataset
DentalClaims. 
Use the geom_jitter() to see the spread of the paid amounts within each provider.

B. 
Add a title for the x-axis, add a title for the y-axis, add a title for the entire chart, and use theme() to change the font size for the titles while also adding a legend.
