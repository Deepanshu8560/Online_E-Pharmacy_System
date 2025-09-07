# Online E-Pharmacy System

**An online pharmacy management system to streamline the process of prescription handling and medicine delivery.**

## Table of Contents
```bash 
- [Overview](#overview)
- [Features](#features)
- [Technology Stack](#technology-stack)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Running the Application](#running-the-application)
- [Project Structure](#project-structure)
- [Usage](#usage)
- [Contributing](#contributing)

```
## Overview
This system enables users (patients, pharmacists, and admins) to interact online—patients can upload prescriptions, pharmacies can manage orders, and admins can oversee the process.

## Features

- Prescription upload and verification
- User authentication and role-based access (admin, pharmacist, patient)
- Order processing with invoice generation
- Inventory and pharmacy management dashboard
- Notifications for order status changes
- Responsive UI for desktop and mobile

## Technology Stack
```bash 
| Layer         | Technologies                        |
|---------------|-------------------------------------|
| Front-end     | (e.g., JSP, HTML, CSS, JavaScript)  |
| Back-end      | (e.g., Java Servlets, JSP, etc.)    |
| Build Tools   | (e.g., Apache Ant/Maven/Gradle)     |
| Web Server    | (e.g., Tomcat)                      |
| Database      | (e.g., MySQL, PostgreSQL)           |

*(Adjust based on your actual stack—looks like a Java web app given directories like `src/com`, `WebContent`, and `build/classes`.)*
```


## Getting Started

### Prerequisites
- Java Development Kit (JDK) >= version X
- Apache Tomcat >= version Y (or any other servlet container)
- Database (e.g. MySQL) and credentials configured

### Installation
1. **Clone the repository:**
   ```bash
   git clone https://github.com/Deepanshu8560/Online_E-Pharmacy_System.git
   cd Online_E-Pharmacy_System

2. Import the project into your IDE (e.g., Eclipse, IntelliJ IDEA).

3. Configure your database connection in src/.../DBConfig.java (or equivalent).

4. Update any necessary configuration files (like web.xml, etc.).

### Running the Application

**Build and deploy on Tomcat:**

mvn clean package  # if using Maven


Or use your IDE to deploy the project to the server.

Access the application via: http://localhost:8080/YourAppName
```bash
Project Structure
├── src/com/...             # Java source files (servlets, controllers, DAOs, models)
├── WebContent/             # Web resources (JSPs, HTML, CSS, JS)
├── build/classes/          # Compiled classes
├── .classpath, .project    # IDE-specific files
├── .settings/              # IDE settings
```

### Usage

- Admin: Manage pharmacies, view orders, modify inventory.

- Pharmacist: Review and process incoming orders, confirm and ship medicines.

_ Patient: Register/login, upload prescriptions, place and track orders.


### Contributing

We welcome contributions! To contribute:

1. Fork the repository.

2. Create a feature branch: git checkout -b feature-name.

3. Commit your changes: git commit -m 'Add feature'.

4. Push your branch and open a pull request.
