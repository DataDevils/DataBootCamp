# Water Data Boot Camp
```
Spring 2018
John Fay & Lauren Patterson
```

## Why this course now?

"The word of the year in the world of water is **digital**"

* Increased recognition that access to water data and analytics is essential to better inform public policies and business decisions.
* Technological advancements in satellites, drones, sensors and so on create more data that can be transformed into actionable information for water management.
* Cultural, academic, and legislative shift towards open water data and transparency.

Sources: [Imagine an Internet of Water](https://www.aspeninstitute.org/aspen-journal-of-ideas/imagine-internet-water/), 
​                [3 Ways the course of water sustainability changed in 2017](https://www.greenbiz.com/article/3-ways-course-water-sustainability-changed-2017)

---

## UNIT 1: How has Falls Lake reservoir impacted streamflow      (*Focus*: EXCEL)

#### What you will learn:

1. The data analysis process.
2. How to find streamflow data.
3. Tools and tricks to answer the following questions in **Excel**:
   * How do monthly streamflows compare?
   * How has the probability of a 100 or 500 year flood changed? 
   * How have minimum streamflows changed? 
     Does the river spend more or less time below the 7Q10 threshold?
   * How has mean annual streamflow changed over time? Before vs after reservoir construction?
4. A teaser showing the same analysis done in the **R** and **Python** scripting environments where the final trend analysis will be done for all streams in North Carolina, with results displayed on a map. 

#### Primary focus:

1. Understanding how to find data.
2. Basic data management skills and documentation.
3. How to manipulate data in Excel:
   * Pivot tables
   * `VLookup` functions
   * `If` statements
   * `SumIf`, `CountIf`, etc.

---

## UNIT 2: Developing Water Balance Sheets from Online Data?   (*Focus*: R *or* Python)

#### What you will learn:

1. R and Python scripting environments.
2. Finding, importing, and "tidying" water use and supply data from on-line repositories.
3. Constructing water usage tables from USGS county level water use data.
4. Downscaling 1/8° degree resolution hydrologic models into county level water supply data. 
5. Combining water use and supply data to construct standard Physical Supply and Use Tables (PSUT).
6. Summarizing data and producing formatted tables and plots.
7. Generating reproducible workflows and documentation.

#### Primary focus (*R*):

1. Introducing R and R Studio.
2. Introducing R-Markdown
3. Basics of syntax and coding in R. 
4. ...

#### Primary focus (*Python*):

1. Introducing Git and GitHub.
2. Introducing Jupyter notebooks. 
3. Basics of syntax and coding in Python:
   * Data types and object oriented programming
   * Variables and collections: Lists, Tuples, Sets, & Dictionaries
4. Retrieving on-line data using the  `requests`, `urllib` packages.
5. Manipulating dimensional data using the `NetCDF4`,  `NumPy` and `Pandas` packages:
   1. Importing and exporting CSV files
   2. Filtering/subsetting records; handling missing data
   3. Grouping and summarizing data
   4. Reshaping, melting, and transposing tables
   5. Combining datasets
   6. Plotting 
6. Spatial analysis with `GeoPandas`, `shapely` and `fiona`:
   1. Constructing spatial objects from coordinate data
   2. Reading in GIS files
   3. Spatial joins
7. Plotting and mapping data using `matplotlib` and `basemaps`.
8. Exporting data into Excel using `openpyxl`.

---

## UNIT 3: How often is Jordan Lake exceeding water quality limits? (Focus: Data Interaction and Visualization)

#### What you will learn: 

1. How to find and download water quality data.
2. How to assess water quality parameters in context with policy thresholds.
3. How to build decision support tools with user inputs in Excel, R, and Python.

#### Primary focus:

1. Building decision-support tools for an end user.
2. Communicating results with data visualization tools.