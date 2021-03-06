# JCPenneyPOM


### Automation of Web Application using POM(PageFactory)+Selenium WebDriver(Java)+Maven+TestNG+Log4j+ExtentReport

This is a sample project to demonstrate testing of JCPenney web application. Test cases under "TestCases folder", are written in excel, and based on it, demonstrated the following concepts.
Data Driven Framework with Page Object Model, Page Factory and how it is used with Selenium WebDriver, Java OOPs concepts, Maven and TestNG functions. 
Implemented Log4j (in "log" folder) to trace logs and to track information. 
Implemented ITestListener interface to generate HTML Extent report with results such as pass/fail/skip. Took screenshot of failed test case and attached it to the report. 

### The Automation routine performs the following actions:
1. Verifies the color, font, and size of the JCPenney logo.

2. Uses the Actions class to mouse hover and selects "Home Electronics" option from "Home & Lifestyle" dropdown menu.

3. Selects "Kids Tech" web element.

4. Selects a product from the Kids Electronics.

5. Adds the product to the cart and proceeds to checkout.

6. Verifies the product is added to the cart.

7. Deletes the product and verifies if the product has been removed from the cart.

### *** Extent Report along with screenshot of failed test case
![JcPenneyExtentReport](https://user-images.githubusercontent.com/61662759/93027505-ec066200-f5d2-11ea-9b36-cb89de64a55e.PNG)

### *** TestNG Test Report
![TestNG-TestReport](https://user-images.githubusercontent.com/61662759/93027396-1efc2600-f5d2-11ea-8c1a-89d971cf6e04.PNG)
