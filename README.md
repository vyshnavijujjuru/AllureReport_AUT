# AllureReport_AUT

nopCommerce website is automated by implementing test cases for opening the logo, login to the website.
## Website
https://demo.nopcommerce.com/

## The following key modules/pages are automated:

- Logo:successful
- Login: error
- Registration:skip

## Technology:
- Tool: Selenium Webdriver
- IDE: Intellij IDEA
- Build tool: <b>Gradle Build</b>
- Language: Java
- Testing Framework : TestNG
## Prerequisite:
- Need to install jdk 11, gradle and allure
- Configure Environment variable for jdk 11, gradle and allure
- Clone this project and unzip it
- Open the project folder
- Double click on "build.gradle" and open it through IntellIJ IDEA
- Let the project build successfully
- Click on "Terminal" and run the automation scripts

## Run the Automation Script by the following command:
- gradle clean test <br>
Selenium will open the browser and start automating.
## After automation to view allure report , give the following commands:

- allure command in cmd <br>

````
allure serve path(allure results path in Intellij IDEA).
````

