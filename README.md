# Hybrid-FrameWork

1. Introduction
The **Hybrid Framework** is a test automation framework that combines features of multiple frameworks such as Data-Driven,pytest. It leverages the advantages of each to create a scalable and flexible automation solution.

2.Technologies Used
- **Programming Language**: Python 
- **Automation Tool**: Selenium 
- **Test Framework**: Pytest
- **Data Management**: Excel 
- **Reporting**:--html Reports
- **Version Control**: Git, GitHub/GitLab
- **CI/CD Tools**: Jenkins, GitHub Actions

3. Project Structure
```
HybridFramework/
│── src/
│   ├── testcases/       
│   ├── screenshoot/        # Test scripts
│   ├── pages/           # Page Object Model classes
│   ├── utils/           # Utility functions
│   ├── data/            # Test data files
│   ├── config/          # Configuration files
│   ├── reports/
|   |--loggs             # Test reports
│── requirements.txt     # Dependencies (for Python projects)
│── pom.xml              # Project documentation
│── README.md           
│── .gitignore          
```

4.Installation
* Prerequisites
- Install Python
- Install Selenium
- Install dependencies:
    
    pip install -r requirements.txt
    pip install pytest
    pip install selenium
    pip install openpyxl
    pip install pytest-xdist
    pip install pytest-htmlreports

5. Running Tests
- To run tests using Pytest:
  pytest -v --html=reports/report.html
6. CI/CD Integration
- Configure Jenkins pipeline to run tests automatically on code commits.
- Use GitHub Actions for triggering automated test runs.

7. Contribution
1. Create a new feature branch (`git checkout -b feature-branch`)
2. Commit changes (`git commit -m 'Add new feature'`)
3. Push to the branch (`git push origin feature-branch`)
4. Create a Pull Request

