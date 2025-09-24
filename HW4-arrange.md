# Homework 4: Arrange Tables

**Due:** *Wednesday*, October 15, 2025 by 11:59pm  
(different deadline due to Fall Break)

The goal of this assignment is to propose and implement charts based on questions/tasks asked about real-world data.  You will be demonstrating that you can choose and implement charts using appropriate idioms for the data and task, incorporating chart design principles that we have covered.

*Read through the entire assignment before starting.*

## Datasets

Choose **one** of the following datasets. You must address **both** questions about your chosen dataset, using a separate chart for each question. 

All of the datasets for this assignment come from the [2010 Statistical Abstract of the United States](https://www.census.gov/library/publications/2009/compendia/statab/129ed.html) (this is different than your HW3 data, which came from the 2012 version).

In addition to looking at the Excel spreadsheets for the tables listed below, you should also view the section's PDF for more information about the data. 

### Dataset 1

[Section 3. Health and Nutrition](https://www.census.gov/library/publications/2009/compendia/statab/129ed/health-nutrition.html) / Table 138 - CHIP Enrollment and Expenditures by State

**Q1:** For each state, show the relationship between enrollment and expenditures for CHIP in 2008. Consider only the 50 US states (Alabama - Wyoming), ignore DC. Highlight any interesting outliers.

**Q2:** Pick 10 states and compare their expenditures between 2000 and 2008. You may pick the 10 states however you wish, but you must discuss how you chose the states.

**Extra Credit [2 points]:** Combine this table with Table 16 (Resident Population by Age and State, from [Section 1 - Population](https://www.census.gov/library/publications/2009/compendia/statab/129ed/population.html)) to show the relationship between CHIP enrollment and 2008 population under 18 years old for each state. You can directly show the numbers or convert to a percentage.

### Dataset 2

[Section 10. National Security and Veterans Affairs](https://www.census.gov/library/publications/2009/compendia/statab/129ed/national-security-veterans-affairs.html) / Table 498. Department of Defense Personnel: 1960 to 2008

**Q1:** Show how the number of the total number of personnel in each of the armed forces (Army, Navy, Marine Corps, Air Force) has changed over time.

**Q2:** Compare the proportion of male to female enlisted for each of the armed forces in 2008. 

**Extra Credit [2 points]:** Combine this table with Table 2 (Population: 1960 to 2008, from [Section 1 - Population](https://www.census.gov/library/publications/2009/compendia/statab/129ed/population.html)) to show the relationship between the total in armed forces service and the US population (use Resident population, including Armed Forces overseas) over time. 

### Dataset 3

[Section 6. Geography and Environment](https://www.census.gov/library/publications/2009/compendia/statab/129ed/geography-environment.html) / Table 379. Highest Temperature of Record - Selected Cities

**Q1:** Choose 5 cities and compare their record highs in each month.  You may pick the 5 cities however you wish, but you must discuss how you chose the cities.

**Q2:** Using the data from all of the cities, which month most often has the highest high? (Hint: For each month, show the number of times it had the highest high for a city.)

**Extra Credit [2 points]:** Combine this table with Table 380 (Lowest Temperature of Record) to show the relationship between each city's annual highest high and annual lowest low.

## Assignment

For your chosen dataset, create a chart to answer each of the questions provided. You will be creating two separate charts. 

As you work through this, pay attention to detail and the visualization principles we have discussed in class when designing your charts.  Charts must have appropriately labeled axes and appropriate unit formats. In your report ([see below](#report)), you will describe the design decisions you have made, so take notes along the way as you work through your design process. 

You may use whatever tool(s) you wish to manipulate the data and create the charts. Remember that CS students must use Python or Vega-Lite to create the charts in at least two HW assignments.

**Additional Extra Credit [4 points]:** Complete Q1 and Q2 for one of the other datasets. You must include a similar writeup for your extra credit charts as for the main assignment.

*All extra credit opportunities are "all or nothing".* You either get the full points or 0 points, no partial extra credit is given.

## Files to Include

Your GitHub repo should contain any files you used to create the charts. This includes smaller datafiles, Excel spreadsheets, Tableau workbooks, Python ipynb notebooks, Python source code, etc. Your repo should also contain images of the created charts so they can be included in your report.

## Report

Your report is an important part of this assignment. It should be written as a narrative and not just a set of bullet points.  Your report should include your name, CS625-HW4, date, and appropriate headings and Markdown markup for clarity and neatness. You will lose points if there are many spelling or grammatical errors. 

Create a section for each question (including extra credit) that you are addressing.  Each section must include the following information:

* question you're addressing
* appropriately-sized image of the chart
* link to the chart
    * Excel, Tableau - link to your spreadsheet/workbook in your GitHub repo
    * Vega-Lite - provide a link to your notebook (see [Note about Using Observable](observable-note.md) for sharing instructions)
    * Seaborn in Google Colab - provide a link to your notebook (make sure to share with GTA and instructor) or link to your ipynb file in your GitHub repo
    * Seaborn locally - link to your Python code in your GitHub repo
    * other tools - ask if you have questions about what should be submitted
* idiom/mark/data/encode table (see [Idiom-Mark-Data-Encode Table Examples](idiom-mark-data-encode-Examples.md))
* explanation of how the idiom used in your chart is appropriate for your datasets and question/task
* discussion of any insights gained about the data from your chart
* discussion of any design decisions you made
* discussion of any special customizations you used

After addressing the assigned questions/tasks, your report must conclude with the following sections:

* Further Questions -  What further questions does your exploration of the dataset prompt?  What hypotheses do you have about what the answers might be?  Are there other tables that might help you address these questions?  
* References - This is where you list any resources you consulted. *It is not acceptable to leave this part blank.* It is OK, and even expected, that you to refer to some code examples, but they must be documented here.

## Submission

You should be working in the private GitHub repo that was created for you in the odu-cs625-datavis organization. If you are working locally, make sure that you have committed and pushed your local repo, including any images you reference, to GitHub.

Submit the URL of your report (not the URL of your repo) in Canvas under HW4. This should be something like

`https://github.com/odu-cs625-datavis/fall25-mcw-username/blob/main/HW4-report.md`

*If you make changes to your report after submitting in Canvas, we will use the last commit time in your repo as your assignment submission time.*
