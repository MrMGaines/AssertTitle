# AssertTitle
Demo project for assertion
Import a webdriver to access different objects/methods etc with "from selenium import webdriver
Create an object for a browser "browser = webdriver.Firefox()" which uses FireFox as your browser
Create a driver file to execute script "browser.get("http://selenium.dev") which will open the Selenium website to be tested in the firefox browser
Open the browser in full screen for better viewing to test "browser.maximize_window()"
Go to website and find the title under "right click, Inspect" to confirm title and create title as a variable "title = browser.title which will have the title of page opened
print(title) prints the title found
"assert "Selenium" in title" confirms that the value of title equals expected value "Selenium" to confirm title is correct.
