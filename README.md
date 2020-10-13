# Pymaceuticals
> This challenge involves analyzing mouse data of 249 mice identified with SCC tumor growth that were treated through a variety of drug regimens.

## General info
Input files are in .csv format & have over 1800 records. The goal is to compare the performance of drug Capomulin vs other treatment regimens.

## Technologies
* conda - version 4.8.3
* jupyter notebook - version 6.0.3

## Code Examples


`Purchasing Analysis:
-used pd.options.display.float_format to format the floats. This gave me the answer in cleaner format.
 
 Gender Demographics:
 -used .map function - mapped dataframe column values with dictionary key - decimal & % format.
 
 Purchasing Analysis(Gender):
 -used reset_index() to 'align' the column names in the o/p dataframe.
 
 Age Demographics & Purchasing Analysis:
 -applied binning. These are tricky.Took a while to narrow down the duplicates from sliced data!
 
 Top Spenders & Most Popular Items:
 -pd.merge!! this took a while to implement. 
 `
## Reading references
Some helpful google reading references:
https://kanoki.org/2019/04/06/pandas-map-dictionary-values-with-dataframe-columns/
https://www.geeksforgeeks.org/how-to-join-pandas-dataframes-using-merge/
