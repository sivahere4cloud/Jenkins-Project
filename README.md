# Jenkins CI/CD Pipeline Automation 🚀

A complete DevOps automation project that demonstrates setting up a Jenkins CI/CD pipeline from scratch on Amazon EC2 using Amazon Linux 2 / Ubuntu 24. This project integrates Git, Maven, SonarQube, Tomcat, S3, and Nexus.

---

## 📌 Project Components

- **Jenkins** (CI/CD tool)
- **Git** (Source control)
- **Maven** (Build tool)
- **SonarQube** (Code quality analysis)
- **Tomcat** (App server for deployment)
- **AWS S3** (Artifact storage)
- **Nexus** (Artifact repository)
- **Ansible** (Optional: Automation tool)
- **EC2** (Compute infrastructure)

---

## 🛠️ Setup Overview

| Component | Instance Type | OS             | Port |
|-----------|----------------|----------------|------|
| Jenkins   | t2.micro        | Amazon Linux 2 | 8080 |
| SonarQube | t2.medium       | Amazon Linux 2 | 9000 |
| Tomcat    | t2.micro        | Amazon Linux 2 | 8080 |
| Nexus     | t2.medium       | Ubuntu 24.04   | 8081 |

---


