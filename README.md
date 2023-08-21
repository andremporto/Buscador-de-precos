![Buscador-de-precos](https://socialify.git.ci/andremporto/Buscador-de-precos/image?description=1&descriptionEditable=Buscador%20de%20pre%C3%A7os%20automatizado%20em%20Python.&forks=1&issues=1&language=1&name=1&owner=1&pattern=Signal&pulls=1&stargazers=1&theme=Auto)
# Automated price comparison project for Google Shopping and Buscapé

### Objective

To train a project in which we have to use web automations with Selenium to fetch the information we need.

### How it works

Imagine that you work in the purchasing department of a company and need to compare suppliers for your inputs/products.

At this point, you will constantly search the suppliers' websites for available products and prices, after all, each of them may offer promotions at different times and with different values.

If the product price is below a limit set by you, you will find the cheapest products and update it in a spreadsheet.

Then, you will send an email with a list of products below your maximum purchase price.

### Alternative

Using APIs (Application Programming Interfaces) can be a powerful solution for automating tasks such as comparing suppliers for purchasing decisions. APIs can provide a structured and efficient way to access data from supplier websites, allowing for real-time price and inventory updates.

With the ability to integrate with other tools and automate workflows, APIs can streamline the procurement process, increasing efficiency and reducing the risk of errors.

Additionally, using APIs can provide a scalable solution for businesses of all sizes, enabling them to leverage the power of technology to make informed purchasing decisions.


### Dataset available

Product Spreadsheet, containing the product names, maximum and minimum prices (to avoid "wrong" or "too good to be true" products), and terms to be excluded from our searches.

### Analysis Roadmap

Search for each product on Google Shopping and Buscapé, and retrieve all results within the price range and are the correct products.

Send an email notification to your email (if it's a company, to the purchasing department, for example), including a table of the items and prices found, along with the purchase link.

### Libraries and databases
 - Pandas
 - Selenium
 - Time
 - Webdriver
