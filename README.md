# 🔍 Wikipedia Test Automation Framework

Professional test automation framework demonstrating **Serenity BDD Screenplay pattern** with Wikipedia search and article validation scenarios.

[![Java](https://img.shields.io/badge/Java-17-orange.svg)](https://www.oracle.com/java/)
[![Selenium](https://img.shields.io/badge/Selenium-4.x-green.svg)](https://www.selenium.dev/)

---

## 🎯 Project Overview

This project showcases enterprise-level test automation practices including:
- **CI/CD integration** with GitHub Actions
- **Comprehensive test reporting** with Serenity BDD

---

## 🛠️ Technologies Used

| Technology             | Purpose |
|------------------------|---------|
| **Java 17**            | Programming language |
| **Serenity BDD**       | Test framework & reporting |
| **Selenium WebDriver** | Browser automation |
| **JUnit 5**            | Test runner |
| **Maven**              | Build & dependency management |
| **GitHub Actions**     | CI/CD pipeline |
| **AssertJ**            | Fluent assertions |

---

## 📋 Test Scenarios

### 🔍 Wikipedia Search & Validation
**Test 1: Reliable Topic Search**
- Search for specific topics (e.g., "cucumber")
- Validate Wikipedia page structure
- Extract and verify page titles
- Demonstrate reliable search patterns

**Test 2: Direct Article Access**
- Open specific Wikipedia articles by exact URL
- Programming languages: Java, Python, Cucumber
- Validate article accessibility
- Verify page content integrity

**Test 3: Multi-Topic Batch Search**
- Batch search across technology stack topics
- Technologies tested: JavaScript, HTML, CSS, React
- Iterative validation approach
- Console logging for test transparency

---

## 🚀 Getting Started

### Prerequisites
```bash
- Java 17 or higher
- Maven 3.9.4 or higher
- Chrome browser (for local execution)
```

### Installation
```bash
# Clone the repository
git clone https://github.com/loko2loko/serenity-junit-screenplay.git

# Navigate to project directory
cd serenity-junit-screenplay

# Run tests
mvn clean verify
```

### Run Specific Tests
```bash
# Run Wikipedia search tests only
mvn test -Dtest=SimpleWikipediaTest

# Run with specific browser
mvn clean verify -Dwebdriver.driver=chrome
```

---

## 📊 Test Reports

After test execution, detailed reports are generated in:
```
target/site/serenity/index.html
```

Reports include:
- Test execution summary
- Step-by-step test scenarios
- Screenshots on failure
- Execution timeline
- Requirements coverage

---

## 🔄 CI/CD Pipeline

Tests run automatically on:
- Every push to `main` branch
- Pull requests
- Scheduled daily runs (optional)

View workflow: [.github/workflows/maven.yml](.github/workflows/maven.yml)

---

## 📁 Project Structure
```
serenity-junit-screenplay/
├── src/
│   └── test/java/
│       └── starter/
│           ├── wikipedia/
│           │   └── SimpleWikipediaTest.java    # Test scenarios
│           └── pages/
│               └── SimpleWikipediaPage.java    # Page Object
├── .github/workflows/      # CI/CD configuration
├── pom.xml                 # Maven dependencies
└── README.md              # This file
```

---

## 🎓 Learning Outcomes

This project demonstrates:
- ✅ Selenium WebDriver best practices
- ✅ CI/CD integration with GitHub Actions
- ✅ Professional test reporting

---

## 👨‍💻 Author

**Marián Koleják**  
QA Automation Engineer | 10+ years experience  
Specializing in: Test Automation, Selenium, Java, CI/CD, Rest API, Kafka

🔗 [LinkedIn Profile](https://www.linkedin.com/in/letomsvatom/)

---

## 📝 License

This project is created for portfolio demonstration purposes.

---

## 🙏 Acknowledgments

Built using Serenity BDD framework and best practices from the test automation community.