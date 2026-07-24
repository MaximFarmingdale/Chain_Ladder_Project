# Chain_Ladder_Project

## Intro 

This project is an analysis of Loss Development Triangles (LDT) of personal auto insurance between State Farm and the rest of the industry. Python is used for data manipulation and writing to Excel, while Excel is used to create an interactive dashboard and a data summary.  

## Data Manipulation

The data is taken from the Casualty Actuarial Society from their chainladders library. Pandas and NumPy are for general data manipulation, while the chainladders library is used for manipulation of LDT objects. The selected LDFs of State Farm personal auto insurance and an aggregate of the rest of the industry is then written to Excel using openpyxl.

## Dashboard Creation

In Excel, in a sheet dedicated to the LDFs, the Cumulative Development Factor for different intervals for a year is calculated, as well as projected ultimate losses for both LDFs. The dashboard contains summary statistics on current and projected ultimate losses and for both LDFs as well as a calculator that takes in LDF model, current amount, current year and modifier to calculate projected losses.
