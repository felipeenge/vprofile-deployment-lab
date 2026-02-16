## 📌 Project Basis

This project was used as a basis for studies and practical deployment.
Original Repository: https://github.com/hkhcoder/vprofile-project

# 🚀 VProfile Deployment Lab

Hands-on project focused on provisioning and deploying the VProfile application in a Linux environment using DevOps practices.

---

## 📌 Objective

Perform a full deployment of the VProfile application by manually configuring all required services and resolving compatibility and dependency issues.

---

## 🏗️ Application Architecture

The application stack includes:

- Java (Tomcat)
- MySQL
- Memcached
- RabbitMQ

---

## ⚙️ Technologies Used

- Linux
- Git
- Apache Tomcat
- MySQL
- Memcached
- RabbitMQ
- Maven

---

## 🔧 Steps Performed

- Cloned the base project
- Built the application using Maven
- Configured the database
- Configured RabbitMQ
- Configured Memcached
- Adjusted Tomcat version (fixed compatibility issue)
- Deployed the `.war` file
- Validated application functionality

---

## 🐛 Issues Encountered

### ❗ Tomcat Version Incompatibility
The application failed to start due to an incorrect Tomcat version installed on the server.
Solution:
Installed the compatible Tomcat version required by the project.

---
