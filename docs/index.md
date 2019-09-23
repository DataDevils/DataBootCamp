---
Title: Data Boot Camp - Overview
Author: John Fay 
Date: Fall 2019
---

# Data Boot Camp - Overview

```
Instructors: John Fay, Edgar Virguez, Jun Shepard
Aug 30 2, 2019 -- GH 1104
```

 ►►==Course survey link:== https://duke.qualtrics.com/jfe/form/SV_54PbMvAq59a5mER ◄◄

## [Course overview](./README.html)

[Why this course now?](./README.html)

### Unit 1: Analyzing water flow data with Excel (Aug 30)

* [Background: How has Falls Lake reservoir impacted streamflow?](./Streamflow_Intro.html#header-n4)

*  [Analytical workflow: A Preview](./Streamflow_Intro.html#header-n14)

* <u>Task</u>: [Exploring monthly stream flows](./Streamflow_Task1.html)

* <u>Task</u>: [Evaluating changes in 100 & 500 year floods](./Streamflow_Task2.html)

* <u>Task</u>: [Evaluating changes in minimum flows](./Streamflow_Task3.html)

* <u>Task:</u> [Evaluating annual stream flow changes over time](./Streamflow_Task4.html)

  ► Completed Excel file → [LINK](./files/Streamflow Data Clayton_KEY.xlsx)
  
  ► Video capture of Unit 1 → [LINK](https://nsoe.capture.duke.edu/Panopto/Pages/Viewer.aspx?id=c3b3586f-b6ad-44a2-a437-aab800e9533d)

---

### Unit 2: Analyzing water flow data with Python & R (Sept 6)

* [Overview & schedule](./Unit2_Schedule.html)
* **Python materials**
  * [00-Setting-up](./python2/00-Setting-up.html)
  * [01-WaterFlow-Terse](https://nbviewer.jupyter.org/github/DataDevils/WaterFlow-Python/blob/master/00-Setting-up.ipynb)
  * [02a-Python-in-5-minutes](https://nbviewer.jupyter.org/github/DataDevils/WaterFlow-Python/blob/master/02a-Python-in-5-minutes.ipynb)
  * [02b-DataFrames](https://nbviewer.jupyter.org/github/DataDevils/WaterFlow-Python/blob/master/02b-DataFrames.ipynb)
  * [03-ImportData](https://nbviewer.jupyter.org/github/DataDevils/WaterFlow-Python/blob/master/03-ImportData.ipynb)
  * [04-Data-Exploration](https://nbviewer.jupyter.org/github/DataDevils/WaterFlow-Python/blob/master/04-Data-Exploration.ipynb)
  * [05-Flood-Frequency-Analysis](https://nbviewer.jupyter.org/github/DataDevils/WaterFlow-Python/blob/master/05-Flood-Frequency-Analysis.ipynb) [optional]
  * [06-Minimum-Flow-Analysis](https://nbviewer.jupyter.org/github/DataDevils/WaterFlow-Python/blob/master/06-Minimum-Flow-Analysis.ipynb) [optional]
  * [07-Trends-Over-Time](https://nbviewer.jupyter.org/github/DataDevils/WaterFlow-Python/blob/master/07-Trends-Over-Time.ipynb) [optional]
  * [08-Show-All-Sites](https://nbviewer.jupyter.org/github/DataDevils/WaterFlow-Python/blob/master/08-Show-All-Sites.ipynb) [optional]
* **R materials**
  * [R set-up and Exploratory Data Analysis](./r/1_LoadStreamflowDescription.html)
  * [Flood return interval](./r/2_Flood_RI_Description.html)
  * [Low flow analysis](./r/3_LowFlowDescription.html)
  * [Trend analysis and Leaflet](./r/4_MannKendall_Description.html)
  * R-scripts: [download](./r/RCran.zip)

► Video capture of Unit 2 → [LINK](https://nsoe.capture.duke.edu/Panopto/Pages/Viewer.aspx?id=fca661b9-c20b-43df-82bd-aac0013a3294)

► Video capture of Unit 2, in R → [LINK](https://nsoe.capture.duke.edu/Panopto/Pages/Viewer.aspx?id=7ecde6e7-157c-4f0d-940f-aac601353b5e)

---

### Unit 3: Data Visualization
* Prep (do before meeting in class!): [Setting Up Your Virtual Machine](./SettingUp_YourVirtualMachine.html)
* [Introduction and overview](Unit3_Intro.html)
* **[Part 1: Getting started with Tableau](./Unit3_Part1_Tableau.html)**
* **[Part 2: Basics of plotting in Python](./Unit3_Part2_Python.html)**
  * Notebook: [Visualization-in-Python](./python3/Visualization-in-Python.html)
  * Notebook: [Mapping-with-plotnine](./Mapping-with-plotnine.html)
  * R-markdown: [USGSWaterPlots](USGSWaterPlots.html)
    * (Raw Rmd [file](https://raw.githubusercontent.com/DataDevils/DataVis/master/rcran/USGSWaterPlots.Rmd))
* **[Part 3: Visualization in action: Water Quality in Jordan Lake](./Unit3_Part3_WaterQualityTask.html)**
  * Python: 
    * [GitHub repo](https://github.com/DataDevils/DataVis): *clone into your [Jupyter environment](https://vm-manage.oit.duke.edu/containers)*
    * [Notebook in HTML format](./python3/Total-Nitrogen.html)
  * R: 
    * [Workspace Zip](./files/rcran.zip) 
    * [Rmd in HTML format](./r3/TotalNitrogen.html)
* **Part 4: R/Shiny example**
  * In action: https://biogas-test.web.duke.edu
  * R-code: https://raw.githubusercontent.com/johnpfay/Biogas_viewer/master/app.R

► Video capture of Unit 3 → [LINK](https://nsoe.capture.duke.edu/Panopto/Pages/Viewer.aspx?id=d1066352-3cf2-4c13-93d2-aacb0145d5c2)

