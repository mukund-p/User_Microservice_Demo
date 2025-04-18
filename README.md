# User Microservice Demo

This project showcases a simple Java-based microservice for user management, integrated with Jenkins for Continuous Integration and Continuous Deployment (CI/CD).

---

## 📁 Project Structure

User_Microservice_Demo/ <br>
├── .mvn/wrapper  <br>
├── src/ <br>
├── .gitignore <br>
├── Jenkinsfile  <br>
├── mvnw <br>
├── mvnw.cmd <br> 
└── pom.xml 


---

## 🚀 Prerequisites

Make sure the following are installed:

- Java Development Kit (JDK 11 or above)
- Apache Maven
- Jenkins (with Git and Maven plugins)
- Git

---

## ⚙️ Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/mukund-p/User_Microservice_Demo.git
cd User_Microservice_Demo
```
### 2. Build the Application
```
./mvnw clean install
```
> On Windows, use `mvnw.cmd clean install`


### 3. Configure Jenkins

- Create a new Pipeline job.
- Set your GitHub repository URL.
- In the Pipeline section, choose "Pipeline script from SCM" and point to the `Jenkinsfile`.

### 4. Run the Pipeline
- Trigger the build manually, OR
- Set up a GitHub webhook for automatic builds on code pushes.
