# Battle-of-the-Lattes

**What is Gini?**
  
  The Gini coefficient, or Gini index
  - used to measure of inequality
  - developed by Italian statistician Corrado Gini (https://ourworldindata.org/what-is-the-gini-coefficient)
  - A Gini index of 0 represents perfect equality
  - an index of 100 implies perfect inequality (https://databank.worldbank.org/metadataglossary/world-development-indicators/series/SI.POV.GINI).

South Korea's Gini index 67.9 , the price of a tall latte is $5.11 CAD. Whereas Hungary's Gini index is 67.7 but the cost of coffee is significantly lower at only $2.69 CAD. Which is very curious. Columbia's export's coffee - that could be a factor in the pricing.

**What Makes Starbucks so Popular?**

Starbucks values innovation, connection and loyalty.https://avada.io/resources/why-starbucks-so-popular.html. Employees are treated well which transfers to the customer and viola! - a brilliant business model. This explains why people around the world continue to frequent this coffee shop.

**The Creation Process**
Using Jupyter Notebook, I used the processes learned throughout this course to extract and scrape the data. The steps are listed below.

**1.  Uploaded Data**

The website https://www.finder.com/ca/starbucks-index supplied visual charts on the cost of a Starbucks tall latte which I uploaded to my notebook.

**2.  The Clean-up Process**

  - used the scrape_table method to make the table Python friendly.
  - created a def to convert the Cost column into a workable float.
  - added the new column to exisiting table.
  - dropped unnecessary columns.

**3.  Adding Country Codes and Currency Exchanges**

  -  created an array with the particular currency exchange from CAD.
  -  created an array which included the country's particular code.
  -  created an array listing the countries used in this study.

**4.  Table Creation**

  -  created a new table using the arrays listed above.
  -  joined both tables together to show prices in both Canadian funds and the country's specific country.
  -  using this new table, I used the barh method to visually represent the cost difference per country.
  -  

**5.  Secondary Source**

  -  found the Gini index for each country represented.
  -  discovered this index has no correlation to the price of a coffee in that region.
