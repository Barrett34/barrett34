# ☁️ Barrett Morrissette | Cloud Engineer & DevOps

### 🚀 Building, Automating & Deploying Cloud Infrastructure

I'm a **Cloud Engineer / DevOps professional** with a background in software development, automation, and technical project management. I'm focused on designing and deploying **scalable cloud infrastructure**, building **CI/CD pipelines**, containerizing applications, and automating cloud environments using **Infrastructure as Code (IaC)**.

My recent projects have focused on building AWS infrastructure with **Terraform**, including networking, compute, container registries, ECS/EKS environments, IAM configurations, and supporting DevOps infrastructure. I've integrated these environments with **Docker, Jenkins, Kubernetes, Helm, GitHub Actions, and Argo CD** to create automated CI/CD and GitOps workflows.

---

## 🛠️ Cloud & DevOps Tech Stack

### ☁️ Cloud

![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge\&logo=amazonaws\&logoColor=white)
![EC2](https://img.shields.io/badge/Amazon_EC2-FF9900?style=for-the-badge\&logo=amazonec2\&logoColor=white)
![EKS](https://img.shields.io/badge/Amazon_EKS-FF9900?style=for-the-badge\&logo=amazoneks\&logoColor=white)
![ECS](https://img.shields.io/badge/Amazon_ECS-FF9900?style=for-the-badge\&logo=amazonecs\&logoColor=white)
![ECR](https://img.shields.io/badge/Amazon_ECR-FF9900?style=for-the-badge\&logo=amazonaws\&logoColor=white)

### 🏗️ Infrastructure as Code & Automation

![Terraform](https://img.shields.io/badge/Terraform-844FBA?style=for-the-badge\&logo=terraform\&logoColor=white)
![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=for-the-badge\&logo=ansible\&logoColor=white)

### ⚙️ DevOps & CI/CD

![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=for-the-badge\&logo=jenkins\&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge\&logo=githubactions\&logoColor=white)
![Argo CD](https://img.shields.io/badge/Argo_CD-EF7B4D?style=for-the-badge\&logo=argo\&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge\&logo=git\&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge\&logo=github\&logoColor=white)

### 📦 Containers & Orchestration

![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge\&logo=docker\&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge\&logo=kubernetes\&logoColor=white)
![Helm](https://img.shields.io/badge/Helm-0F1689?style=for-the-badge\&logo=helm\&logoColor=white)

### 💻 Development & Systems

![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge\&logo=linux\&logoColor=black)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge\&logo=gnubash\&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge\&logo=python\&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge\&logo=flask\&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge\&logo=nodedotjs\&logoColor=white)

---

# 🚀 Featured Cloud & DevOps Projects

## ☸️ AWS EKS CI/CD & GitOps Deployment

Built an end-to-end DevOps environment for deploying a containerized **Python Flask application to Amazon EKS**, with the supporting AWS infrastructure provisioned using **Terraform Infrastructure as Code**.

### 🔧 Technologies

`AWS` `Terraform` `EKS` `ECR` `EC2` `IAM` `Docker` `Kubernetes` `Jenkins` `Helm` `GitHub Actions` `Argo CD` `Linux`

### 🏗️ What I Built

* 🏗️ Built the AWS infrastructure using **Terraform Infrastructure as Code (IaC)**
* ☁️ Provisioned an **Amazon EKS** environment and supporting AWS resources through Terraform
* 🐳 Containerized a Python Flask application using **Docker**
* 📦 Stored and managed container images using **Amazon ECR**
* 🔄 Built a **Jenkins CI/CD pipeline** to automate application delivery
* ☸️ Automated Kubernetes deployments using **Helm**
* 📈 Configured Kubernetes **Horizontal Pod Autoscaling (HPA)**
* 🔐 Configured AWS **IAM roles and policies** required by the deployment environment
* 🔑 Integrated **GitHub Actions with AWS using OIDC**
* 🔁 Created a separate **GitOps deployment workflow**
* 🚀 Implemented continuous deployment using **Argo CD**
* ❤️ Verified Kubernetes deployments were **Healthy & Synced**
* 🌐 Exposed the application through AWS load-balancing infrastructure
* 🧪 Troubleshot IAM, Kubernetes, Jenkins, networking, authentication, and deployment issues

### 🔄 CI/CD & GitOps Flow

```text
Developer
    │
    ▼
GitHub
    │
    ├──────────── CI/CD ─────────────┐
    │                                │
    ▼                                ▼
Jenkins                         GitHub Actions
    │                                │
    ▼                                ▼
Docker Build                   AWS OIDC
    │                                │
    ▼                                ▼
Amazon ECR                     Amazon ECR
    │
    ▼
Helm
    │
    ▼
Amazon EKS
    │
    ▼
Kubernetes Pods

GitOps Branch
    │
    ▼
Argo CD
    │
    ▼
Amazon EKS
```

---

## 🐳 AWS ECS Microservices Deployment

Built a cloud deployment environment for separate **React frontend** and **Node.js/Express backend** services using containerized microservices and Terraform-managed AWS infrastructure.

### 🔧 Technologies

`AWS` `Terraform` `ECS` `Fargate` `ECR` `Docker` `Jenkins` `React` `Node.js` `Express`

### 🏗️ What I Built

* 🏗️ Defined AWS infrastructure using **Terraform IaC**
* ☁️ Provisioned AWS resources required for the application environment
* 🐳 Dockerized frontend and backend applications independently
* 📦 Created separate **Amazon ECR repositories** for frontend and backend images
* 🚀 Built the deployment architecture around **Amazon ECS/Fargate**
* 🔄 Worked with **Jenkins CI/CD** architecture for automated delivery
* 🌐 Configured separate application ports for frontend and backend services
* 🧪 Tested Docker containers locally before cloud deployment
* 🛠️ Troubleshot container networking and port conflicts
* ♻️ Managed infrastructure lifecycle using `terraform init`, `plan`, `apply`, and `destroy`

---

## 🌐 AWS Infrastructure & Cloud Networking

Built AWS networking and compute infrastructure to create secure **public/private cloud architectures**.

### 🔧 Technologies

`AWS` `Terraform` `VPC` `EC2` `IAM` `NAT Gateway` `Internet Gateway` `Security Groups` `NACLs`

### 🏗️ What I Built

* 🏗️ Defined cloud infrastructure using **Terraform**
* 🌐 Built custom AWS **VPC networking**
* 🌍 Created public and private subnets
* 🚪 Configured an **Internet Gateway** for public connectivity
* 🔄 Configured a **NAT Gateway** for private subnet outbound connectivity
* 🗺️ Created and configured route tables
* 🔒 Configured **Security Groups**
* 🛡️ Worked with **Network ACLs**
* 💻 Provisioned **EC2 instances**
* 🔑 Configured AWS **IAM users, groups, roles, and policies**
* 🔐 Implemented **MFA** for IAM access
* 🧪 Tested connectivity between cloud resources

---

## 🤖 Ansible Multi-Server Automation

Automated Linux server configuration across multiple AWS EC2 instances using **Ansible**.

### 🔧 Technologies

`Ansible` `AWS EC2` `Linux` `SSH` `Nginx`

### 🏗️ What I Built

* 🖥️ Provisioned multiple AWS EC2 web servers
* 🎛️ Configured an **Ansible control server**
* 📋 Created and managed Ansible inventory
* 🔑 Configured SSH key authentication between servers
* 🤖 Created and executed **Ansible playbooks**
* 🌐 Automated **Nginx installation and configuration**
* 🧪 Verified connectivity across multiple servers
* 🚀 Automated repeatable server configuration instead of manually configuring each instance

---

## 🔄 Jenkins CI/CD Automation

Built Jenkins pipelines on AWS infrastructure to automate application build and deployment workflows.

### 🔧 Technologies

`Jenkins` `AWS EC2` `GitHub` `Docker` `Linux` `Bash`

### 🏗️ What I Built

* ☁️ Hosted Jenkins on an **Ubuntu EC2 instance**
* 🔗 Integrated Jenkins with **GitHub source control**
* 📝 Created **Jenkinsfiles** defining CI/CD pipeline stages
* 🐳 Automated Docker image builds
* 📦 Integrated container registry workflows
* 🚀 Automated application deployment stages
* 🔐 Configured Jenkins credentials and AWS permissions
* 🖥️ Worked directly with Linux servers through SSH and Bash
* 🧪 Troubleshot pipeline dependencies, permissions, paths, credentials, and deployment failures

---

# 🧠 Current Focus

```yaml
cloud:
  - AWS
  - Cloud Architecture
  - Cloud Networking
  - IAM & Security

infrastructure_as_code:
  - Terraform
  - Reusable Infrastructure
  - Infrastructure Automation

devops:
  - CI/CD
  - Jenkins
  - GitHub Actions
  - GitOps
  - Argo CD

containers:
  - Docker
  - Kubernetes
  - Amazon EKS
  - Amazon ECS
  - Helm

systems:
  - Linux
  - Bash
  - Ansible
```

---

# 🏗️ My DevOps Workflow

```text
Plan
  ↓
Infrastructure as Code
  ↓
Terraform
  ↓
AWS Infrastructure
  ↓
Application Code
  ↓
Git / GitHub
  ↓
CI/CD
  ↓
Docker Build
  ↓
Amazon ECR
  ↓
ECS / EKS
  ↓
Deploy
  ↓
Monitor
  ↓
Improve
```

---

# 🎯 Engineering Interests

☁️ **Cloud Infrastructure**

🏗️ **Infrastructure as Code**

⚙️ **DevOps Engineering**

🐳 **Containerization**

☸️ **Container Orchestration**

🔄 **CI/CD Automation**

🚀 **GitOps**

🌐 **Cloud Networking**

🔐 **Cloud Security & IAM**

🤖 **Infrastructure Automation**

📊 **Monitoring & Observability**

---

# 📚 Continuous Learning

I'm continuing to expand my cloud engineering knowledge through hands-on projects involving:

* AWS architecture
* Terraform & Infrastructure as Code
* CI/CD pipeline design
* GitOps workflows
* Infrastructure security
* Monitoring and observability
* High availability and scalability
* Cloud cost optimization

---

# 🤝 Let's Connect

I'm interested in opportunities involving **Cloud Engineering, DevOps Engineering, Infrastructure Automation, and Cloud Operations**.

💼 **LinkedIn:** https://www.linkedin.com/in/barrett-morrissette/
📧 **Email:** morrissettebarrett@gmail.com


---

### 💡 *Build it. Automate it. Deploy it. Improve it.* ☁️🚀
