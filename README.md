\# Selenium E-Commerce Automation Framework



A Page Object Model (POM)-based test automation framework built with Java, Selenium WebDriver, and TestNG to automate end-to-end test scenarios for the \[SauceDemo](https://www.saucedemo.com/) e-commerce web application.



\---



\## About

Developed by \*\*Dipanshu Yadav\*\* to demonstrate real-world test automation skills including framework design, POM architecture, and end-to-end test coverage.



\---



\## Test Coverage

21 automated test cases covering:

\- Login scenarios (valid, invalid, locked out, empty fields)

\- Add/remove items from cart

\- Complete end-to-end checkout flow

\- Logout from multiple pages

\- Empty cart and edge case verification



\---



\## Tech Stack

\- Java JDK 20

\- Selenium WebDriver 3.141.59

\- TestNG 6.14.3

\- WebDriverManager 5.4.1

\- Maven

\- Chrome Browser



\---



\## Project Structure



selenium-ecommerce-framework/

├── src/

│   ├── main/java/

│   │   ├── drivers/

│   │   │   └── BrowserFactory.java

│   │   └── pages/

│   │       ├── BasePage.java

│   │       ├── LoginPage.java

│   │       ├── InventoryPage.java

│   │       ├── CartPage.java

│   │       ├── CheckoutStep1Page.java

│   │       ├── CheckoutStep2Page.java

│   │       └── CheckoutCompletePage.java

│   └── test/java/

│       ├── TestBase/

│       │   └── TestBase.java

│       └── TestCases/

│           ├── LoginTest.java

│           └── StandardUser\_PurchaseTest.java

├── testng.xml

└── pom.xml



\---



\## How to Run



Clone the repository:

```bash

git clone https://github.com/dipanshhhu/selenium-ecommerce-framework-.git

```



Run via Maven:

```bash

mvn clean test

```



Or right click `testng.xml` in IntelliJ → Run



\---



\## Design Pattern

This framework follows the \*\*Page Object Model (POM)\*\* design pattern where each web page has a dedicated Java class containing its elements and actions. This ensures clean separation of test logic from UI interaction code, making tests easy to maintain and scale.



\---



\## Website Under Test

\[https://www.saucedemo.com](https://www.saucedemo.com) 

