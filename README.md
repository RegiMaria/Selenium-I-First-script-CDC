About the tool **Selenium**:

Selenium is an open-source set of tools and libraries used for software testing automation in web applications. It allows developers and testers to automate the interaction of a browser with a web application, simulating actions a user would take, such as clicking buttons, filling out forms, navigating between pages, etc.

Objective:

1. Open the web page of the CDC (Center of Disease Control and Prevention).
2. Work with CSS selectors.
3. Download a PDF file.

Note: I added a short wait for the download and disabled `driver.quit()`. Therefore, close the browser yourself!

So, let's get started!

1. Install Selenium: `pip install selenium`
2. Install the WebDriver - 'ChromeDriver - WebDriver for Chrome' if you are using Chrome.
3. Import the modules and libraries for browser interaction:
   - `from selenium import webdriver`
   - `from selenium.webdriver.common.by import By`

About:

- 'Webdriver': Although "webdriver" is often associated with Selenium, it refers to the `webdriver` class that is part of the Selenium library.
- 'By (Locating Strategies)': `By` is a class in the `selenium.webdriver.common.by` module, which is part of the Selenium WebDriver. It provides different locating strategies to find elements on the page.

Tools used:

- Selenium
- Jupyter Notebook

