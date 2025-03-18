# Hybrid-FrameWork

## Introduction
The **Hybrid Framework** is a test automation framework that combines features of multiple frameworks such as Data-Driven,pytest. It leverages the advantages of each to create a scalable and flexible automation solution.

## Features
- **Modular Design**: Test scripts are broken into reusable modules.
- **Data-Driven Testing**: Supports external data sources like Excel, CSV, and databases.
- **Keyword-Driven Approach**: Uses predefined Data Driven for test execution.
- **Page Object Model (POM)**: Enhances maintainability and readability.
- **Logging & Reporting**: Integrated with --html/Allure reporting.
- **Parallel Execution**: Supports execution across multiple browsers and environments.
- **CI/CD Integration**: Easily integrates with Jenkins, GitHub Actions, and other CI/CD tools.

## Technologies Used
- **Programming Language**: Python 
- **Automation Tool**: Selenium 
- **Test Framework**: Pytest
- **Data Management**: Excel 
- **Reporting**:--html Reports
- **Version Control**: Git, GitHub/GitLab
- **CI/CD Tools**: Jenkins, GitHub Actions

## Project Structure
```
HybridFramework/
│── src/
│   ├── testcases/       
│   ├── keywords/        # Test scripts
│   ├── pages/           # Page Object Model classes
│   ├── utils/           # Utility functions
│   ├── data/            # Test data files
│   ├── config/          # Configuration files
│   ├── reports/         # Test reports
│── requirements.txt     # Dependencies (for Python projects)
│── pom.xml              # Project documentation
│── README.md           
│── .gitignore          
```

## Installation
### Prerequisites
- Install Python
- Install Selenium
- Install dependencies:
    
    pip install -r requirements.txt
    pip install pytest
    pip install selenium
    pip install openpyxl
    pip install pytest-xdist
    pip install pytest-htmlreports

## Running Tests
- To run tests using Pytest:
  pytest -v --html=reports/report.html
## CI/CD Integration
- Configure Jenkins pipeline to run tests automatically on code commits.
- Use GitHub Actions for triggering automated test runs.

## Contribution
1. Fork the repository
2. Create a new feature branch (`git checkout -b feature-branch`)
3. Commit changes (`git commit -m 'Add new feature'`)
4. Push to the branch (`git push origin feature-branch`)
5. Create a Pull Request

