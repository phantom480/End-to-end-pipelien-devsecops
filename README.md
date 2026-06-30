# 🚀 End-to-End DevSecOps CI/CD Pipeline on AWS

**Welcome to the End-to-End DevSecOps CI/CD Pipeline Project!**

This project demonstrates how to automate the complete software delivery lifecycle using modern **DevOps** and **DevSecOps** practices. It covers infrastructure provisioning, continuous integration, security scanning, containerization, Kubernetes deployment, and monitoring on AWS.

The project showcases a production-inspired CI/CD pipeline built using **Terraform, Jenkins, Docker, Kubernetes, SonarQube, Trivy, OWASP Dependency Check, Prometheus, and Grafana**.

---

# 🛠️ Tools & Technologies Used

| **Category** | **Tools** |
|--------------|-----------|
| **Cloud Platform** | ![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white) |
| **Version Control** | ![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white) |
| **Infrastructure as Code** | ![Terraform](https://img.shields.io/badge/Terraform-623CE4?style=flat-square&logo=terraform&logoColor=white) |
| **CI/CD** | ![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=flat-square&logo=jenkins&logoColor=white) |
| **Code Quality** | ![SonarQube](https://img.shields.io/badge/SonarQube-4E9BCD?style=flat-square&logo=sonarqube&logoColor=white) |
| **Containerization** | ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) |
| **Container Registry** | ![Docker Hub](https://img.shields.io/badge/DockerHub-2496ED?style=flat-square&logo=docker&logoColor=white) |
| **Container Orchestration** | ![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white) |
| **Security** | ![SonarQube](https://img.shields.io/badge/SonarQube-4E9BCD?style=flat-square&logo=sonarqube&logoColor=white) ![OWASP](https://img.shields.io/badge/OWASP-000000?style=flat-square&logo=owasp&logoColor=white) ![Trivy](https://img.shields.io/badge/Trivy-00979D?style=flat-square&logo=trivy&logoColor=white) |
| **Monitoring** | ![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white) ![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white) |
| **Operating System** | ![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black) |

---

# 📌 Project Objectives

✅ Automate infrastructure provisioning using Terraform

✅ Build an automated CI/CD pipeline using Jenkins

✅ Perform Static Code Analysis with SonarQube

✅ Scan dependencies using OWASP Dependency Check

✅ Scan Docker Images using Trivy

✅ Build and Push Docker Images to Docker Hub

✅ Deploy applications to Kubernetes

✅ Monitor infrastructure using Prometheus & Grafana

✅ Follow DevSecOps Best Practices

---

# 🚦 Project Workflow

## **Phase 1: Infrastructure Provisioning**

- Provision AWS infrastructure using Terraform
- Create VPC, Networking, Security Groups, and Compute Resources
- Configure Kubernetes Cluster

---

## **Phase 2: Continuous Integration (CI)**

- Push source code to GitHub
- Jenkins automatically triggers the pipeline
- Checkout source code
- Install project dependencies
- Perform SonarQube Static Code Analysis
- Validate SonarQube Quality Gate

---

## **Phase 3: DevSecOps Security Scanning**

- Perform OWASP Dependency Check
- Scan application filesystem using Trivy
- Detect vulnerable packages
- Scan Docker Images before deployment

---

## **Phase 4: Containerization**

- Build Docker Image
- Tag Docker Image
- Push Image to Docker Hub

---

## **Phase 5: Kubernetes Deployment**

- Deploy application to Kubernetes Cluster
- Create Deployment
- Create Service
- Verify Pods
- Verify Application Availability

---

## **Phase 6: Monitoring & Observability**

- Configure Prometheus
- Collect Application Metrics
- Visualize Metrics using Grafana
- Monitor Container Health
- Monitor Resource Utilization

---

# 🔄 CI/CD Pipeline

```
Developer

↓

GitHub

↓

Webhook

↓

Jenkins

↓

Checkout Source Code

↓

SonarQube Analysis

↓

Quality Gate

↓

OWASP Dependency Check

↓

Trivy File Scan

↓

Docker Build

↓

Trivy Image Scan

↓

Push Docker Image

↓

Deploy to Kubernetes

↓

Prometheus Monitoring

↓

Grafana Dashboard
```

---

# 📊 Monitoring Stack

- Prometheus
- Grafana
- Blackbox Exporter
- Application Health Monitoring
- Container Monitoring
- Resource Monitoring

---

# 🔒 Security Features

✔ SonarQube Static Code Analysis

✔ OWASP Dependency Check

✔ Trivy Filesystem Scan

✔ Trivy Docker Image Scan

✔ Vulnerability Detection

✔ Secure CI/CD Pipeline

---

# 📁 Project Structure

```bash
.
├── Jenkinsfile
├── Dockerfile
├── terraform/
├── kubernetes/
├── monitoring/
│   ├── prometheus.yml
│   └── grafana/
├── src/
├── README.md
```

---

# 🚀 Getting Started

Clone the repository

```bash
git clone https://github.com/<your-username>/<repository-name>.git

cd <repository-name>
```

Initialize Terraform

```bash
terraform init
terraform plan
terraform apply
```

Deploy Kubernetes Resources

```bash
kubectl apply -f kubernetes/
```

Run Jenkins Pipeline

```
Build Now
```

---

# 📷 Screenshots

Add screenshots for:

- Jenkins Pipeline
- SonarQube Dashboard
- OWASP Report
- Trivy Scan Report
- Docker Hub Repository
- Kubernetes Pods
- Prometheus Targets
- Grafana Dashboard
- Running Application

---

# 🎯 Future Enhancements

- Add Alertmanager
- Slack Notifications
- Email Alerts
- GitHub Actions Support
- ArgoCD GitOps Deployment
- Helm Charts
- HashiCorp Vault Integration
- Kubernetes HPA
- AWS Load Balancer Controller
- GitLeaks Secret Scanning

---

# ⭐ If you found this project useful, please give it a Star!
![Terraform](https://img.shields.io/badge/Terraform-IaC-623CE4?logo=terraform)
![AWS](https://img.shields.io/badge/AWS-Cloud-232F3E?logo=amazonaws)
![Jenkins](https://img.shields.io/badge/Jenkins-CI%2FCD-D24939?logo=jenkins)
![Docker](https://img.shields.io/badge/Docker-Container-2496ED?logo=docker)
![Kubernetes](https://img.shields.io/badge/Kubernetes-Orchestration-326CE5?logo=kubernetes)
![Prometheus](https://img.shields.io/badge/Prometheus-Monitoring-E6522C?logo=prometheus)
![Grafana](https://img.shields.io/badge/Grafana-Dashboard-F46800?logo=grafana)
![License](https://img.shields.io/badge/License-MIT-green)
