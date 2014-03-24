#Cinnamon

Cinnamon is a Force.com native app that enables you to build and execute Selenium-based GUI tests from within your Salesforce org to validate Visualforce pages in your Salesforce org.

* Create and execute Selenium Tests from within your Salesforce org
* Out-of-box integration with Sauce Labs which provides comprehensive OS/Browser coverage
* Connect to any of your Salesforce DE or Sandbox org via OAuth authentication
* Provide PageObject support to help develop maintainable test code to interact with your Visualforce pages

##Install
1. Install [Apex Selenium package](https://login.salesforce.com/packaging/installPackage.apexp?p0=04t30000001I916)
2. Install [Cinnamon package](https://login.salesforce.com/packaging/installPackage.apexp?p0=04td0000000N0pW)

##Setup

Go to "Settings" and provide the following Selenium config settings and enter your Sauce Labs username & access key

* Selenium Proxy URL `ondemand.saucelabs.com`
* Selenium Port `80`

Connect to your org under test

Run a sample Cinnamon Test

##Issues/Bugs
Use [Github Issues](https://github.com/ryojiosawa/cinnamon/issues) to log and track issues and bugs
