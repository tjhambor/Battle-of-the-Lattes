# Battle-of-the-Lattes

**What is Gini?**
  
  The Gini coefficient, or Gini index
  - used to measure of inequality
  - developed by Italian statistician Corrado Gini 
  - A Gini index of 0 represents perfect equality
  - an index of 100 implies perfect inequality 

South Korea's Gini index 67.9 , the price of a tall latte is $5.11 CAD. Whereas Hungary's Gini index is 67.7 but the cost of coffee is significantly lower at only $2.69 CAD.

**What is Mean Wealth?**

Mean wealth divides the accumulative wealth by the total number of adults in that country.

South Korea's mean wealth is $311,707 CAD and Hungary's mean wealth is $80,166 CAD. This difference causes one to make a correlation between the price of a cup of coffee in relation to that country's mean wealth.

**What Makes Starbucks so Popular?**

Starbucks values innovation, connection and loyalty.. Employees are treated well which transfers to the customer and viola! - a brilliant business model. This explains why people world wide continue to frequent this coffee shop.

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
  -  created an Income Factor table listing all the countries and their Gini Index and their Mean Wealth.
![Tall Latte Pricing barh](https://github.com/tjhambor/Battle-of-the-Lattes/assets/152350152/c23ab4b7-b85e-4f40-8047-266c371ddc8f)
![Mean Wealth barh-2](https://github.com/tjhambor/Battle-of-the-Lattes/assets/152350152/3735166a-35e5-46a4-ad16-1c6237c7c171)
![Gini Index barh-3](https://github.com/tjhambor/Battle-of-the-Lattes/assets/152350152/8a10572c-0cd8-4e41-9e76-f29adde47596)


**5.  Secondary Source**

  -  found the Gini index for each country represented.
  -  discovered this index has no correlation to the price of a coffee in that region.
  -  found the Mean Wealth for each country represented.
  -  discovered Mean Wealth has some correlation to the price of coffee in that region.

**Conclusion**

There was no conclusive evidence that a country's Gini index was a influencing factor on the price of a Starbucks tall latte. My intention was to create a joined table between the coffee cost and the Gini% table, unfortunately I was unable to complete this task so I have included the graph for all the countries including their Gini index.

** Work Cited**

(https://ourworldindata.org/what-is-the-gini-coefficient)
(https://databank.worldbank.org/metadataglossary/world-development-indicators/series/SI.POV.GINI)
(https://avada.io/resources/why-starbucks-so-popular.html)
