---
Title: Analysis of Streamflow Data using Excel
Author: Lauren Patterson and John Fay
Date: Spring 2018
---

[Water Data Boot Camp: Spring 2018](./index.html)

# Unit 1: Task 4<br>Exploring trends in streamflow over time

## Background

Water security is becoming increasingly important as population and water demand continue to grow. This is especially true with changing climate conditions that introduce new variability into our expectations of water supply. Briefly, we want to know whether the average annual streamflow has changed over time. 

## Set up

- Create a new spreadsheet and name it `Trends`.
- Create a table of `Year`, `Total Streamflow`, and `Count`.
  - Copy and Paste the entire Water Year column from the EDA tab in the `Year` column. 
    - Remove duplicate values: **Data menu**>**Data Tools**>**Remove Duplicates**
  - ``Use `SUMIF` and `COUNTIF` to calculate the number of observations per year and the annual streamflow
  - Remove those years with < 90% of data (i.e., fewer than 329 records in a year) , 
    - Use `IF` to calculate and flag rows.
- Plot streamflow over time and add a linear trend line
- Go to **File** > **Options** >**Add-ins** > **Analysis Toolpack**
  - **Data Menu** > **Data Analysis** > **Regression**
  - Run the regression analysis on the data
    - Turn on all the plots
    - Is the trend significant?
- Repeat for 1930-1980 and for 1984-2017
  - What to you observe? 
  - Are the trends obvious? 

## More Practice

If there are not annual trends, are there seasonal ones? What about February and August?

- ##### Grab all *February* values:

  - Go to the working spreadsheet and `filter` by month
  - `AVERAGEIF` the filtered data...

- ##### Repeat the above analysis

  - *What do you observe?*


---

## EXCEL Limitations

Excel is a wonderful tool; however, it also has several limitations.

1. Very limited analytical pack. Indeed, many of the statistical methods used for water resources rely are non-parametric, meaning they do not assume linear relationships between x and y variables. 

2. It is time consuming to repeat analyses over multiple sites. What if we wanted to look at all downstream gauges from Falls Lake?

3. It is difficult to replicate results in Excel. Sometimes data are copied and pasted as values rather than formulas. Sometimes errors are hand corrected and not marked. 

   ​

Statistical programs and coding are valuable tools that readily address these three limitations in excel: (1) diverse statistical packages, (2) batch capable, and (3) reproducible.