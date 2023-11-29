# Battle-of-the-Lattes

**What is Gini?**
  The Gini coefficient, or Gini index
  - used to measure of inequality
  - developed by Italian statistician Corrado Gini (https://ourworldindata.org/what-is-the-gini-coefficient)
  - A Gini index of 0 represents perfect equality
  - an index of 100 implies perfect inequality (https://databank.worldbank.org/metadataglossary/world-development-indicators/series/SI.POV.GINI).

South Korea's Gini index 67.9 , Hungary 67.7 China 70.9The findings found in this report would indicate massive financial inequality among countries. For example, in Sweden the Gini is calculted at 87.4 and the price of a Starbucks tall latte is $5.72CAD. Columbia's Gini is slightly less coming in at 83.1 but they pay significantly less for the same coffee for only $2.69CAD.

**What Makes Starbucks so Popular?**
Like the Apple products, Starbucks carries with it a certain amount of pop and circumstance. Holding a Starbucks coffee can elicit a sense of pride and oppulence. Marketing has played a huge role from their humble beginnings.

**The Creation Process**
Using Jupyter Notebook, I used the processes learned throughout this course to extract and scrape data. The steps are listed below.

**1.  Uploaded Data**

The website https://www.finder.com/ca/starbucks-index supplied visual charts on the cost of a Starbucks tall latte which I uploaded to my notebook.

**2.  The Clean-up Process**

  - used the scrape_table method to make the table Python friendly.
  - created a def to convert the Cost column into a workable float.
  - added the new column to exisiting table.
  - found the max and min latte amounts (this was more for curiousity than anything else)
  - dropped unnecessary columns.

**3.  Adding Country Codes and Currency Exchanges**

  -  created an array with the particular currency exchange from CAD.
  -  created an array which included the country's particular code.
  -  created an array listing the countries used in this study.

**4.  Table Creation**

  -  created a new table using the arrays listed above.
  -  joined both tables together to show prices in both Canadian funds and the country's specific country

**5.  
