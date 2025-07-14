# 🏥 Medicure – DevOps Pipeline for Healthcare

> A healthcare domain DevOps project that simulates managing and deploying a hospital chain’s digital infrastructure using full CI/CD automation.  
> Covers cloud provisioning, automated deployments, containerization, monitoring, and testing.

---

## 🧰 Tech Stack & Tools

- **Cloud Platform**: AWS (EC2, IAM, VPC, S3)
- **CI/CD**: Git, GitHub, Jenkins
- **Containerization**: Docker
- **Orchestration**: Kubernetes (2-node cluster)
- **Infrastructure as Code**: Terraform
- **Configuration Management**: Ansible
- **Monitoring**: Prometheus, Grafana
- **Testing**: Selenium, JUnit, TestNG
- **Languages**: Java (Spring Boot), Bash, YAML

---

## 🚀 Key Features

- ✅ Mavenized Spring Boot microservice for doctor data management
- ✅ CI/CD pipeline from GitHub → Jenkins → Docker → Kubernetes
- ✅ Infrastructure automation using Terraform & Ansible
- ✅ Application monitoring using Prometheus & Grafana
- ✅ End-to-end test automation with Selenium
- ✅ Separate environments: Dev, Prod, Monitoring, Jenkins, Terraform, Selenium

---

## 📦 Folder Structure

├── docker/ # Dockerfile and docker-compose
├── jenkins/ # Jenkinsfile, jobs, and pipeline logic
├── kubernetes/ # YAMLs for deployment, services, configmaps
├── terraform/ # Terraform files for AWS infra provisioning
├── ansible/ # Playbooks to configure EC2 and deploy app
├── monitoring/ # Prometheus and Grafana config
├── tests/ # Selenium + JUnit tests and reports
└── README.md
