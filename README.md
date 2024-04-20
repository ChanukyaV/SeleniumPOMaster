# SeleniumPOMaster Framework with Cucumber

This repository contains a Maven project implementing a robust automation framework for web application testing using Selenium WebDriver, Java, Page Object Model (POM), and Cucumber. The framework is designed to facilitate efficient and maintainable automated testing practices.

## Key Features
- Page Object Model (POM): Modularizes web pages into separate classes, improving code maintainability and reusability.
- Cucumber Integration: Utilizes Cucumber for behavior-driven development (BDD) testing, allowing test scenarios to be written in natural language using Gherkin syntax.
- Assertions and Reporting: Provides custom assertion methods and generates detailed test reports with screenshots and logs for effective test result analysis.

## Prerequisites
- Java Development Kit (JDK)
- Maven
- IDE (Eclipse, IntelliJ IDEA, etc.)
- Web browser drivers (ChromeDriver, GeckoDriver, etc.)

## Getting Started

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/yourusername/selenium-java-pom-framework.git
   ```

2. Open the project in your preferred IDE.

3. Review and configure the project settings, dependencies, and browser configurations as needed.

4. Write feature files using Gherkin syntax in the `src/test/features` directory.

5. Implement step definitions in Java under the `src/test/java/stepdefinitions` package.

6. Execute the tests using Maven commands or IDE test runners.

## Project Structure

```
selenium-java-pom-framework/
├── src/
│   ├── main/
│   │   ├── java/
│   │   │   └── com.ae.pages/           # Page classes
│   │   │   └── com.ae.util/            # Utility classes
│   ├── test/
│   │   ├── java/                 # Test runners
│   │   │   └── stepdefinitions/  # Step definition classes         
│   │   └── features/             # Cucumber feature files    
│   └── ...
├── pom.xml                       # Maven project configuration file
└── ...
```

## Contributing

Contributions are welcome! Please feel free to submit pull requests or open issues for any improvements or feature requests.
