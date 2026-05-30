# Gradle-sampleApp

A professional, production-ready **Java Application** initialized and managed using **Gradle 9.5.1** and **Java 21**. This project demonstrates a clean project setup, testing configuration, and local build automation.

## 🛠️ Tech Stack & Features
* **Language:** Java 21 (LTS)
* **Build Tool:** Gradle 9.5.1 (Groovy DSL)
* **Testing Framework:** JUnit Jupiter (JUnit 5)
* **Architecture:** Single Application Structure

## 🚀 Getting Started

### Prerequisites
Make sure you have the following installed locally:
* [Java Development Kit (JDK) 21](https://oracle.com)
* Git

### Installation & Cloning
```bash
git clone https://github.com
cd Gradle-sampleApp
```

### Running the Application
You can run the application directly using the bundled Gradle Wrapper (`gradlew`):

**On Windows:**
```cmd
gradlew.bat run
```

**On Linux/macOS:**
```bash
./gradlew run
```

### Running Tests
To execute the automated JUnit Jupiter test suite, run:
```bash
./gradlew test
```

## 📂 Project Structure
```text
Gradle-sampleApp/
├── app/
│   ├── src/
│   │   ├── main/java/      # Application source code
│   │   └── test/java/      # Unit test cases
│   └── build.gradle        # App-specific build configuration
├── gradlew                 # Gradle Wrapper script for Unix
├── gradlew.bat             # Gradle Wrapper script for Windows
└── settings.gradle         # Project structure settings
```
