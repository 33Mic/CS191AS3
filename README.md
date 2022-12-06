# Toyota Corolla
## But why?
Initially, I was searching for a product that I knew for sure had very different prices around the world so that it would be more interesting to do the data analysis, as there would be a multitude of reasons for the price differences. I was well aware that car prices are different around the world. Like in my country Pakistan, we have 200 percent import duties on cars, making it very expensive to buy a car, compared to a place like Dubai where there are barely any taxes when you buy a car.


*Note: We also kept in mind that a good product to use for our index should be something akin to being a necessity.*  
## Steps or method we used to create our index (brief description of each code cell):

General Overview of our process
Using Jupyter Notebooks, we organized and analyzed our data using techniques learnt in CMPUT 191. We used a combination of web scraping, requesting from an API and good old fashioned data cleaning. 

- After finding a site (https://www.numbeo.com/cost-of-living/prices_by_country.jsp?displayCurrency=USD&itemId=206) that had information on Toyota Corolla prices by country, we had to use web scraping techniques learned in class to create a table we could work with. 
- Imported a local currencies table in order to assign every individual country a unique currency code (joined the two tables)
- We also found, imported and cleaned a table with information on tax rates per country. However we decided not to factor in GST to the sale price as we found that car prices are impacted by many other taxes, duties and customs depending on the country. 




## Graphs
![Horizontal Bar Graph](Horizontal Bar Graph.png)
### A lesser title
Maybe I can finally have this work properly
