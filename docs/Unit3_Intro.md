---
Title: Unit 3 - Data Visualization(Intro)
Author: Lauren Patterson and John Fay
Date: Spring 2018
---

# Unit 3: Data Visualization 

### Conceptual Introduction to Visualization

Data visualizations are the modern equivalent of visual communication with the goal of better communicating numerical information to an audience. Interactive visualizations allow the audience to explore and engage with the data that is of particular interest to them. Effective visualizations make complex data more accessible, understandable, and usable.

Visualizations take many shapes and forms, and like any form of communication, a great deal of artful creativity accompanies whatever scientific method in devising the best visualizations. That said, however, a few key principles go a long way in thinking about visualizing data. 

First, visualization is all about patterns, about categorizing or aggregating data in meaningful ways, and then revealing these patterns in ways that require the least amount of brain power. And so, when looking at our raw data, we need to identify which fields might serve as categories or <u>dimensions</u>, and which fields might serve as <u>numeric values</u> and how those numeric values might be <u>aggregated</u> in meaningful ways. 

Second, visualization is about communicating a <u>message</u> to an <u>audience</u>. Visualization software allow us an enormous variety of visualization options to choose from. However, in some cases one simple number may be the most effective means to communicate a results. What decides this is knowing what exactly it is you want to communicate with your product, i.e. your message, and to whom you are communicating, i.e., your audience. 

Finally, <u>experience</u> is key to getting better at constructing visualizations. Again, like writing or other forms of communication, you get better the more you do. Take a moment to reflect on what you like or don't like about other  visualizations you see. Also, seek other's opinion about ones you create. Develop your own common sense about what makes a good visualization!



### Visualization tools

There are a plethora of tools to help researchers display their data to a broader audience. Some of these tools are:

- **Shiny R**: https://shiny.rstudio.com/

  - Shiny is an R package that enables users to build interactive web apps within R by accessing html and javascript libraries.

- **Python**: many libraries (such as Bokeh and pandas) can be used to create interactive data visualizations. Python also has tools such as:

  - **Dash** - [https://medium.com/@plotlygraphs/introducing-dash-5ecf7191b503](https://medium.com/@plotlygraphs/introducing-dash-5ecf7191b503)

- **Tethys Platform**: http://www.tethysplatform.org/

  - Uses Python to create interactive data visualizations specifically around water resources

- **Tableau**: https://www.tableau.com/

  * Uses spreadsheets (such as Excel) to create data visualizations and storyboards. 

In the interest of time, we are going to explore **Tableau**. Unlike **R** or **Python** based visualization tools, Tableau is proprietary software. As a student, you can string along as many free 1-year licenses as you want (as long as you remain a student), but if you want to continue using Tableau beyond academia, you'll need to pay for it. However, Tableau's learning curve is much shorter, allowing us to dive deeper into aspects of data visualization.  



### Downloading and installing Tableau

Tableau is <u>not</u> installed on NSOE machines. Instead, you'll need to install your own copy. You can either apply for a 1-year license of the full desktop edition or download the free public version here: https://public.tableau.com/s/download/public/pc64 . The key difference between the two is that the public version does not allow you to save your Tableau workbooks... 



---

## Unit overview

#### Part 1: Introduction to Tableau

We begin with a crash course on Tableau, using it to import, explore, and visualize **water use data** compiled from the USGS. Learning objectives include:

* Importing data into Tableau
* Manipulating and organizing data
  * Discussing data formats and proper data structuring for visualization
* Plotting in Tableau: Bar plots, horizontal bar plots, pie charts, & choropleth maps
* Creating dashboards and storyboards
* Uploading your results to Tableau's server for sharing

#### Part 2: Basics of plotting [in Python]

* Using `pandas` and`matplotlib` for quick plots.
* When and where to use different plots: line, bar, pie charts
* Plot aesthetics: feature colors, figure sizes, colormaps, marker and line types
* Using `seaborn` for more complex plots: countplots and heatmaps
* Using 'folium' for map visualizations

#### Part 3: Visualization in context : Water quality in Jordan Lake

1. Identifying and procuring water quality data in the Jordan Lake region
2. Loading, exploring, and tidying site data
3. Loading, exploring and tidying measurement data
4. Combining site and measurement data 
5. Combining nutrient concentration with flow data to compute daily loads
6. Comparing daily loads with TMDL limits

#### Part 4 (time permitting): Exploring R/Shiny and Plotly/Dash

* R-Shiny apps from the user's perspective
* R-Shiny apps from the developers perspective
* The `Plotly` and `Dash` packages for Python