# Data-Scraping-Project

My Data sources are going to be 2 pages from the HEB product list online, at the following urls
https://www.heb.com/category/shop/fruit-vegetables/fruit/berries-cherries/490082/490334
https://www.heb.com/category/shop/fruit-vegetables/vegetables/mixed-vegetables/490083/490350

Specifically I intend to extract the following data tables:
Price, Unit Price, Name, Catagory, SubCatagory
Total price of product, price per weight, Name of product, Type of product(i.e. produce), sub type of product(i.e fruit)

I intend to do some simple transformations, grabbing total price, name, type, etc. Price per weight will need to be derived in some cases. In addition type and subtype will be added in depending on where the data is scraped from.


The end goal of this project is to scrape all of HEB's product catalog into a postgress data base. These 5 catagories should be enough to use that as a basis for an app that I am planning to create.
