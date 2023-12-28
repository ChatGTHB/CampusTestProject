![Maven Central](https://img.shields.io/maven-central/v/org.seleniumhq.selenium/selenium-java?versionSuffix=4.11.0&label=Selenium)
![Maven Central](https://img.shields.io/maven-central/v/io.cucumber/cucumber-java?versionSuffix=7.9.0&label=Cucumber)
![Maven Central](https://img.shields.io/maven-central/v/org.testng/testng?versionSuffix=7.7.0&label=TestNG)
![Maven Central](https://img.shields.io/maven-central/v/org.slf4j/slf4j-api?versionSuffix=1.8.0-beta2&label=Slf4j)
![Maven Central](https://img.shields.io/maven-central/v/org.apache.commons/commons-lang3?versionSuffix=3.12.0&label=Apache%20Commons)
![Maven Central](https://img.shields.io/maven-central/v/tech.grasshopper/extentreports-cucumber7-adapter?versionSuffix=1.9.2&label=Grashopper)
[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)

# CampusTestProject

In this project we use Java, TestNG, Cucumber, Gherkin and other Java tools on this project.

Domain: https://test.mersys.io/

##Team-01 

- Cihat Köse - QA Lead - Norway 
- Ahmet Serdar Yılmaz - QA Tester - Switzerland
- Zafer Yılmaz - QA Tester - Germany
   
Getting Started
---------------

The easiest way to get started is to clone the repository:

```bash
# File > New > Project From Version Control 
# Copy to URL
git@github.com: https://github.com/ChatGTHB/CampusTestProject
# open project at Intellij
# select project JDK
jdk11

# Open Module Settings at Intellij
# install selenium from maven
org.seleniumhq.selenium:selenium-java:4.11.0

# install io.cucumber from maven
cucumber-java version :7.9.0

# install io.cucumber TestNG from maven
cucumber-TestNG version:7.9.0

# install TestNG from maven
org.testNG:7.7.0

# install slf4j from maven
org.slf4j:slf4j-api:1.8.0-beta2

# install slf4j from maven
org.slf4j:slf4j-simple:1.8.0-beta2

# install org.apache.commons from maven
org.apache.commons-lang3 version:3.12.0

# install tech.grasshopper from maven
extentreports-cucumber7-adapter version:1.9.2

# install org.apache.poi from maven
poi version: 4.1.1

# install org.apache.poi from maven
poi-ooxml version: 4.1.1

# install commons.io from maven
commons-io:commons-io:2.11.0

# install mysql-connector-java from maven
mysql version: 8.0.18

# install com.github.javafaker from maven
javafaker version: 1.0.2

# Right click to Main.java
Run 'Main'

```
List of Dependencies
----------------

| Package      | Description                                                |
|--------------|------------------------------------------------------------|
| TestNG       | Next Generation Testing Tool.                              |
| Selenium     | Browser Automation Framework.                              |
| slf4j        | The Simple Logging Facade for Java.                        |
| commons.io   | The Apache Commons IO library.                             |
| apache poi   | Extracting and Sending Information from/to Outside Sources |
| cucumber     | Cucumber is a tool that supports BDD.                      |
| grasshopper  | HTML & PDF Report tool.                                    |
| javafaker    | Generate Random Data                                       |
| mysql        | Create SQL Inquiries                                       |

## File Structure
```bash
|-- src
|   |-- main
|       |-- java
|       |-- resources
|
|   |-- test
|       |-- java
|           |-- apachePOI
|           |-- featureFiles
|               |-- Cucumber Feature Files
|           |-- jdbc
|           |-- pages
|               |-- Locators, Page Object Model Files
|               |-- Hooks
|           |-- runners
|               |-- CrossBrowserTest
|               |-- ExtentReport
|           |-- stepDefinitions
|               |-- Test Class Files
|           |-- utilities
|               |-- Events
|               |-- GWD
|           |-- XML
|       |-- resources
|       |-- results
|           |-- reports*
|           |-- gitignore
|
|-- gitignore
|-- pom.xml

## Rules Of Pull Request
- Update your codes from main branch before you pull request
- Don't use Thread.Sleep
- Don't use Turkish Character
- Don't use extra space
- Use logical comment lines
- Use ./screenshots folder for bug & facility report
- Only work at your story
- Don't add any scenario you want

## License

This project is open-sourced software licensed under the [MIT license](http://opensource.org/licenses/MIT).

### Wish you the best! 


