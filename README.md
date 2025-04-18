# Hello Java Maven

A simple Java "Hello, Jenkins + Maven!" application built to demonstrate a basic Maven build job using Jenkins.

## 📁 Project Structure

hello-java-maven/ ├── pom.xml └── src/ └── main/ └── java/ └── HelloWorld.java


## 🔧 Tools Used

- Java JDK 11
- Maven 3.8.6
- Jenkins (via Docker)

## 🚀 How It Works

1. Created a simple Java project with a `HelloWorld.java` class.
2. Configured `pom.xml` for Maven build.
3. Ran Jenkins in Docker:
   ```bash
   docker run -p 8080:8080 jenkins/jenkins:lts
   
   ```
4. Set up a Jenkins Freestyle project with clean package goal.
5. Build executed successfully with BUILD SUCCESS message.

📌 Outcome
Successfully built a Java Maven project using Jenkins, demonstrating basic CI workflow.

