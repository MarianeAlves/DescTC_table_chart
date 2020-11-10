# DescTC( )

When it comes to real-world-data, very often it needs some sort of cleansing job to be done. Missing values and syntax errors are commonly found on databases and we spend most of our time trying to fix them up. 

In order to reduce this time spent, I decided to design a tool that provides you with a wider and quicker vision of the variables that need to be adjusted before you start your own analysis.

Methods provided:

 *DescTC.table( )* 

    Offers you the following information of each quantitative/qualitative variable:

    - Type 
    - Quantity of zero numbers
    - Quantity of NaN's
    - % of NaN's 
    - Quantity of uniques values 
    - Quantity of outliers 
    - Min value / Lowest category 
    - Mean
    - Median
    - Moda
    - Max value / Highest category
    

 *DescTC.chart( )*

    Condense large amounts of information of each variable into easy-to-understand formats 
    that clearly and effectively communicate important points:

    - Plot the distribution of each variable 
    - Box plot of each quantitative variables
    - Plot the correlation between quantitative variables
    
*Please be aware that your data must be converted to a pandas DataFrame with column names.
