# 🛒 E-Commerce Test Automation Framework

Professional test automation framework demonstrating **Serenity BDD Screenplay pattern** with real-world e-commerce test scenarios.

![Tests](https://github.com/loko2loko/serenity-junit-screenplay/workflows/Build/badge.svg)
[![Java](https://img.shields.io/badge/Java-17-orange.svg)](https://www.oracle.com/java/)
[![Selenium](https://img.shields.io/badge/Selenium-4.x-green.svg)](https://www.selenium.dev/)

---

## 🎯 Project Overview

This project showcases enterprise-level test automation practices including:
- **Screenplay Pattern** for maintainable test code
- **Page Object Model** implementation
- **CI/CD integration** with GitHub Actions
- **Comprehensive test reporting** with Serenity BDD
- **Cross-browser testing** capabilities

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

---

## 📋 Test Scenarios

### User Authentication
- ✅ Valid user login
- ✅ Invalid credentials handling
- ✅ Session management

### Shopping Cart Operations
- ✅ Add products to cart
- ✅ Remove products from cart
- ✅ Update quantities
- ✅ Cart persistence

### Product Search & Filtering
- ✅ Search functionality
- ✅ Filter by category
- ✅ Sort options

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
│   └── test/java/          # Test scenarios
│       ├── starter/        # Test classes
├── .github/workflows/      # CI/CD configuration
├── pom.xml                 # Maven dependencies
└── README.md              # This file
```

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