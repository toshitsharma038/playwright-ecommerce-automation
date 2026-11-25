# Playwright E-Commerce Automation Framework

A hands-on UI Automation Framework using **Playwright with JavaScript**, following the Page Object Model (POM) design pattern.

## Project Objective

Build a real-world E-Commerce Automation Framework covering UI automation, API testing, test architecture, reporting, and CI/CD integration.

## Tech Stack

- JavaScript
- Node.js
- Playwright
- Playwright Test
- Git & GitHub
- GitHub Actions (Planned)

## Project Structure

```text
playwright-ecommerce-automation/
│
├── .github/
│   └── workflows/
│       └── playwright.yml
│
├── pages/
│   └── LoginPage.js
│
├── tests/
│   ├── example.spec.js
│   └── login.spec.js
│
├── .gitignore
├── package.json
├── package-lock.json
├── playwright.config.js
└── README.md
```

## Learning & Implementation Roadmap

### 1. Playwright Fundamentals

- [x] Node.js and npm setup
- [x] Playwright installation
- [x] Project initialization
- [x] First Playwright test execution
- [x] Headless and Headed execution
- [ ] Playwright architecture
- [ ] Browser, BrowserContext, and Page
- [ ] Playwright configuration

### 2. Locators

- [ ] getByRole()
- [ ] getByText()
- [ ] getByLabel()
- [ ] getByPlaceholder()
- [ ] getByTestId()
- [ ] locator()
- [ ] CSS and XPath selectors
- [ ] Chained locators
- [ ] Multiple matching elements
- [ ] nth(), first(), last()
- [ ] Filtering locators

### 3. Assertions & Synchronization

- [ ] toHaveURL()
- [ ] toHaveTitle()
- [ ] toBeVisible()
- [ ] toBeEnabled()
- [ ] toHaveText()
- [ ] toHaveValue()
- [ ] Auto-waiting
- [ ] Explicit waits
- [ ] Handling timeouts

### 4. Page Object Model (POM)

**Status: In Progress**

- [x] Create pages folder
- [x] Create LoginPage.js
- [x] Create LoginPage class
- [x] Initialize Page in constructor
- [x] Define login page locators
- [x] Create reusable login methods
- [x] Import Page Object into test file
- [ ] Implement ProductsPage
- [ ] Implement CartPage
- [ ] Implement CheckoutPage
- [ ] Implement reusable navigation methods
- [ ] Complete E-Commerce POM architecture

### 5. Test Execution & Management

- [ ] Test.describe()
- [ ] Test.beforeEach()
- [ ] Test.afterEach()
- [ ] Test.skip()
- [ ] Test.only()
- [ ] Test.fail()
- [ ] Test tagging
- [ ] Parallel execution
- [ ] Retries
- [ ] Cross-browser execution

### 6. Fixtures & Hooks

- [ ] Built-in fixtures
- [ ] Custom fixtures
- [ ] Test fixtures
- [ ] Worker fixtures
- [ ] Fixture setup and teardown
- [ ] Reusable authentication fixture

### 7. E-Commerce Test Scenarios

- [ ] Valid login
- [ ] Invalid login
- [ ] Empty username and password
- [ ] Product listing validation
- [ ] Product sorting
- [ ] Add product to cart
- [ ] Remove product from cart
- [ ] Cart validation
- [ ] Checkout process
- [ ] Order confirmation
- [ ] Logout

### 8. Advanced Playwright Concepts

- [ ] Dropdown handling
- [ ] Checkboxes and radio buttons
- [ ] Alerts and dialogs
- [ ] Frames and iframes
- [ ] Multiple tabs and windows
- [ ] File upload
- [ ] File download
- [ ] Screenshots
- [ ] Videos and traces
- [ ] Network interception
- [ ] Authentication and storage state

### 9. Data-Driven Testing

- [ ] Test data using arrays
- [ ] JSON test data
- [ ] Excel-based test data
- [ ] Parameterized tests
- [ ] Environment variables
- [ ] Multiple test users

### 10. API Testing

- [ ] GET request
- [ ] POST request
- [ ] PUT request
- [ ] PATCH request
- [ ] DELETE request
- [ ] API response validation
- [ ] Status code validation
- [ ] API authentication
- [ ] UI and API integration testing

### 11. Framework Architecture

- [ ] Common utility methods
- [ ] Reusable test data
- [ ] Environment configuration
- [ ] Global setup and teardown
- [ ] Custom assertions
- [ ] Error handling
- [ ] Logging
- [ ] Maintainable framework design

### 12. Reports & Debugging

- [ ] HTML reports
- [ ] List reporter
- [ ] Allure reporting
- [ ] Screenshots on failure
- [ ] Trace viewer
- [ ] Debugging with VS Code
- [ ] Test execution analysis

### 13. GitHub & CI/CD

- [x] Git initialization
- [x] GitHub repository creation
- [x] Push local project to GitHub
- [ ] Git branching
- [ ] Pull and merge changes
- [ ] GitHub Actions workflow
- [ ] Automated test execution
- [ ] CI pipeline execution
- [ ] Publish test reports as artifacts

## Current Implementation

Currently, the project has:

- Playwright installed and configured.
- Basic test execution working.
- Login Page Object created.
- Login test created.
- Basic POM implementation in progress.

## Application Under Test

**SauceDemo:** https://www.saucedemo.com/

The application will be used to implement and practice E-Commerce test scenarios.

## Run Tests

Run all tests:

```bash
npx playwright test
```

Run a specific test:

```bash
npx playwright test tests/login.spec.js
```

Run tests with visible browser:

```bash
npx playwright test tests/login.spec.js --headed
```

Open HTML report:

```bash
npx playwright show-report
```

## Learning Approach

This project is being developed step by step. Each concept will first be understood, then implemented, tested, and committed to GitHub.

**Goal:** Build a maintainable, reusable, and industry-oriented Playwright Automation Framework.
