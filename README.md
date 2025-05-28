# CI/CD Pipeline with Blue-Green Deployment using Azure DevOps

This project demonstrates a robust, cloud-native CI/CD pipeline using Azure DevOps, hosted on Azure App Service, and implements a blue-green deployment strategy for zero-downtime releases. The pipeline automates build, test, and deployment stages, ensuring high reliability, fast delivery, and safe rollbacks.

---

## 🚀 Project Overview

- **Automated CI/CD:** Source code changes trigger builds, automated tests, and deployments via Azure DevOps pipelines.
- **Blue-Green Deployment:** Uses Azure App Service deployment slots to enable seamless, zero-downtime production releases and instant rollbacks.
- **Cloud Hosting:** Application is hosted on Azure App Service, benefiting from managed infrastructure, auto-scaling, and integrated security.

---

## 🛠️ Technologies Used

- Azure DevOps (Pipelines, Repos)
- Azure App Service (Deployment Slots)
- YAML Pipeline Definitions
- Git
- [Your App Stack: Node.js/.NET/Python, etc.]

---

## 📈 Pipeline Workflow

1. **Code Commit:** Developers push changes to Azure Repos.
2. **Build (CI):** Azure DevOps builds the project, runs tests, and publishes artifacts.
3. **Release (CD):** Pipeline deploys to the staging (green) slot on Azure App Service.
4. **Validation:** Automated/manual tests run on the green slot.
5. **Slot Swap:** After approval, the green slot is swapped with production (blue), making the new version live.
6. **Rollback:** If issues arise, instantly swap back to the previous slot.

---

## 🌟 Key Features

- Automated build and release using Azure DevOps
- Source control integration with Azure Repos
- Pre-deployment approvals and quality gates
- Seamless slot swapping for zero-downtime deployment
- Easy rollback to previous stable version
- End-to-end logging and monitoring

---

## 📷 Project Screenshots.


### 1. Azure DevOps Build Pipeline
![alt text](image-3.png)
### 2. Azure DevOps Release Pipeline
![alt text](image-2.png)
![alt text](image-7.png)
![alt text](image-1.png)
### 3. Deployment Slots in Azure App Service
![alt text](image.png)
### 4. Othe Screenshots
![alt text](image-4.png)
![alt text](image-5.png)
![alt text](image-6.png)
---

## 📝 How to Use

1. Clone the repository and review the pipeline YAML definitions.
2. Connect your Azure DevOps project and Azure App Service.
3. Configure deployment slots (blue and green) in Azure App Service.
4. Trigger the pipeline via code commit or manual run.
5. Monitor the deployment process and approve slot swaps as needed.

---

## 🎯 Learning Outcomes

- Hands-on experience with Azure DevOps CI/CD pipelines
- Implementing blue-green deployment using Azure App Service slots
- Automating cloud deployments for high availability
- Configuring approvals, gates, and quality checks
- Gaining practical DevOps and cloud release management skills

---

## 📚 References

- [Blue-Green Deployment using Azure DevOps (YouTube)](https://www.youtube.com/watch?v=acJErWFS15w&list=PLI4APkPHzsUXseJO1a03CtfRDzr2hivbD&index=6&ab_channel=TechTutorialswithPiyush)

---

