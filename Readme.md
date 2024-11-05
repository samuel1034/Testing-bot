# **ISIPay Web Module Testing**

This repository contains automated tests for ISIPay’s web module, covering essential functionality including login, registration, 2FA, Google Sign-In, KYC, password recovery, and crypto transactions. Using Python and Selenium WebDriver, these tests interact with the ISIPay web application to validate usability and functionality, capturing screenshots and logging results in a Word document for analysis.

## **Features**

* **Login and Registration Testing:** Tests login, Google Sign-In, account creation, and 2FA workflows.
* User Authentication: Verifies 2FA, password recovery, and email receipt processes.
* Crypto Transactions: Tests sending/receiving crypto, viewing transaction history, and P2P interactions.
* User Interface: Validates buttons, menus, and critical UI elements.
* Prerequisites
Python 3.10+: Ensure Python is installed and in your PATH.

* Selenium: Install Selenium with pip install selenium.

* Chrome WebDriver: Place the chromedriver.exe in your system path or specify its location in the script.
docx Module: Install with pip install python-docx.

##  _**Installation**_

## **Clone this repository:**


``git clone https://github.com/your-username/isipay-web-testing.git```

## Navigate to the directory:

`cd isipay-web-testing`

## Running Tests

Ensure chromedriver.exe is available in the specified location.
Run the main testing script:

`python main.py`

Results will be saved as screenshots in the screenshots directory, and logs will be recorded in Resultados_Prueba_Modulo_Web.docx.
Script Structure

##### main.py: Contains the main test functions, helper methods, and screenshot capture.

##### **Screenshot Storage: All screenshots from test runs are saved in the screenshots folder.**

##### Test Logs: Results are documented in Resultados_Prueba_Modulo_Web.docx.

## Customization

You can adjust elements like wait times, URL paths, and element selectors in main.py based on the ISIPay web structure.

**Troubleshooting
Timeout Errors:** Increase wait times in WebDriverWait.

**Missing Elements:** Ensure element selectors match the latest UI structure.

**ChromeDriver Compatibility:** Verify chromedriver.exe matches the installed Chrome version.