# my-login-test

This repository contains a basic Selenium WebDriver test using TestNG that performs a login test on the [Sauce Demo](https://www.saucedemo.com/) website.

## Project Overview

- Opens Chrome browser
- Navigates to https://www.saucedemo.com/
- Enters valid username and password
- Clicks the login button
- Verifies successful login by checking the page title text
- Closes the browser after the test

## Prerequisites

- Java JDK 8 or higher installed
- [ChromeDriver](https://sites.google.com/chromium.org/driver/) executable downloaded and its path set in the code (`System.setProperty`)
- Maven or your preferred build tool (if you want to run via Maven)
- TestNG framework installed or configured in your IDE
- Google Chrome browser installed

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
