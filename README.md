# Pymaceuticals
> This challenge involves analyzing mouse data of 249 mice identified with SCC tumor growth that were treated through a variety of drug regimens.

## Table of contents
* [General info](#general-info)
* [Technologies](#technologies)
* [Code Examples](#codeexamples)

## General info
Input files are in .csv format & have over 1800 records. The goal is to compare the performance of drug Capomulin vs other treatment regimens.

## Technologies
* jupyter notebook - version 6.0.3

## Code Examples

`Data Cleaning:
-merged the files and identified the duplicates using .loc and .duplicated
-used boolean statement on df column "Mouse ID" !=g989
 
 Bar and Pie charts:
 -used group by and count. The tick locations generated were horizontal, changed to vertical using rotation=90
 
 Quartiles, Outliers and Boxplots:
 -used isin, sort and drop duplicates to clean the mouse data.
 
 Line and Scatter Plots:
<<<<<<< HEAD
 -used loc to get data associated with a particular mouse ID and used plot grid.
 -looking at data grouped by mouse ID.

=======
 -
 

 
>>>>>>> fb4c8d46c07ac4e30aa56723d7edfe7d82f22be3
 `

