The project is an automation test suite for testing the Juice Shop web application. It is built using the following frameworks:

Selenium WebDriver: For browser automation.
TestNG: For managing and running tests.
Page Object Model (POM): For creating maintainable and reusable page classes.
Maven: For dependency management and running the tests.

The project follows the Page Object Model (POM) design pattern for better maintainability and scalability. Here's the basic structure of the project:

HomePage.java: Page object representing the homepage of Juice Shop with methods related to home page actions.
JuiceShopAutomation.java: Contains TestNG tests for performing different actions on the Juice Shop site 
ProductPage.java: Contains methods to interact with the product page (e.g., clicking on a product, expanding reviews).
LoginPage.java: Contains methods for login functionality.
BasketPage.java: Contains methods for interacting with the shopping basket.
CheckOutPage.java: Contains methods to interact with the checkout process.
Product.java: Contains the methids for the specific product page
TestNG XML Suite: Defines the test suite with parameters for running tests on different browsers.
