# Playwright Automation Testing with CI/CD Pipeline

An automated testing framework built using **Python**, **Playwright**, and **Pytest**, integrated with **GitHub Actions** for Continuous Integration and Continuous Delivery (CI/CD).

## 🚀 Features
* **Cross-Browser Testing:** Powered by Playwright to support Chromium, Firefox, and WebKit.
* **Page Object Model (POM):** Clean and maintainable test architecture separating test scripts from page locators and actions.
* **Automated CI/CD:** GitHub Actions workflow configured to automatically execute test suites on code pushes and pull requests.
* **HTML Test Reports:** Generates detailed test reports for execution tracking.

---

## 📁 Project Structure

CI-CD-Pipeline-AutomationTesting/
│
├── .github/
│   └── workflows/        # GitHub Actions CI/CD pipeline configuration
├── pages/                # Page Object Model classes
├── tests/                # Test scripts (e.g., test_saucedemo.py)
├── reports/              # Generated test execution reports
├── pytest.ini            # Pytest configuration file
├── requirements.txt      # Project dependencies
└── README.md             # Project documentation
