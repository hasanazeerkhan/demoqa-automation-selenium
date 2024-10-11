# Alerts Automation with Selenium

This repository contains automated tests for the Alerts functionality on [demoqa.com](https://demoqa.com/alerts) using Selenium with JavaScript.

## Table of Contents

- [Introduction](#introduction)
- [Prerequisites](#prerequisites)
- [Technologies used](#technologies-used)
- [Installation](#installation)
- [Running the Tests](#running-the-tests)
- [Test Cases](#test-cases)
- [Contributing](#contributing)

## Introduction

This project aims to automate the testing of alert functionalities available on the demoqa.com website. It covers various alert types, including simple alerts, confirmation alerts, and prompt alerts, ensuring expected behaviors are maintained.

## Prerequisites

Before you begin, ensure you have met the following requirements:

- Node.js (version 14 or later)
- npm (Node package manager)
- Selenium WebDriver for JavaScript
- A web browser (e.g., Chrome, Firefox)

## Technologies used
<p align="left"> <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="javascript" width="80" height="80"/> </a> <a href="https://www.selenium.dev" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/detain/svg-logos/780f25886640cef088af994181646db2f6b1a3f8/svg/selenium-logo.svg" alt="selenium" width="80" height="80"/> </a> </p>

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/alerts-automation-selenium.git
   ```

2. Navigate into the project directory:

   ```bash
   cd alerts-automation-selenium
   ```

3. Install the dependencies:

   ```bash
   npm install selenium-webdriver
   ```

4. Install the browser driver (e.g., ChromeDriver for Chrome):

   ```bash
   npm install chromedriver
   ```

## Running the Tests

To execute the test suite, run:

```bash
node test.js
```

Ensure that your browser is installed and the driver is configured correctly.

## Test Cases

The following test cases are included in this repository:

1. **Simple Alert**: Verify the behavior of the simple alert.
2. **Confirmation Alert**: Check the acceptance and rejection of the confirmation alert.
3. **Prompt Alert**: Validate input handling in the prompt alert.

Feel free to expand or modify these tests based on your needs.

## Contributing

Contributions are welcome! If you have suggestions for improvements or bug fixes, please create an issue or submit a pull request.

1. Fork the project.
2. Create your feature branch `git checkout -b feature/YourFeature`
3. Commit your changes `git commit -m 'Add some feature'`
4. Push to the branch `git push origin feature/YourFeature`
5. Open a pull request.

## Folder structure

The project follows a simple structure with the following directories:

```
├── AlertsFrameWindows
    │── alerts.js
    │── browser-windows.js
    │── frames.js
    │── modal-dialogs.js
    │── nestedframes.js

├── BookStoreApplication
    │── books.js
    │── profile.js
    │── login.js

├── Elements
    │── buttons.js
    │── checkBox.js
    │── dynamic-properties.js
    │── links.js
    │── radioButton.js
    │── textBox.js
    │── upload-download.js
    │── webtables.js

├── Forms
    │── automation-practice-form.js

├── Interactions
    │── dragabble.js
    │── droppable.js
    │── resizable.js
    │── selectable.js
    │── sortable.js

├── Widgets
    │── accordian.js
    │── auto-complete.js
    │── date-picker.js
    │── menu.js
    │── progress-bar.js
    │── select-menu.js
    │── slider.js
    │── tabs.js
    │── tool-tips.js
```
