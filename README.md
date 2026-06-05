# Selenium E-Commerce Automation Framework

A Page Object Model (POM)-based test automation framework built with Java, Selenium WebDriver, and TestNG to automate end-to-end test scenarios for the [SauceDemo](https://www.saucedemo.com/) e-commerce web application.

## About
Developed by **Dipanshu Yadav** to demonstrate real-world test automation skills including framework design, POM architecture, and end-to-end test coverage.

## Test Coverage
21 automated test cases covering login scenarios, add/remove cart items, complete checkout flow, logout from multiple pages, and edge case verification.

## Tech Stack
Java JDK 20 | Selenium WebDriver 3.141.59 | TestNG 6.14.3 | WebDriverManager 5.4.1 | Maven | Chrome

## How to Run
Clone the repository and run via Maven:
```bash
git clone https://github.com/dipanshhhu/selenium-ecommerce-framework-.git
cd selenium-ecommerce-framework-
mvn clean test
```
Or right click `testng.xml` in IntelliJ and select Run.

## Design Pattern
This framework uses the **Page Object Model (POM)** — each web page has a dedicated Java class separating test logic from UI interaction code, making tests easy to maintain and scale.

## Website Under Test
https://www.saucedemo.com