DevOps Project - Calculator App
This is a DevOps Project that demonstrates how to set up and manage a simple Calculator App using Azure DevOps Services, Docker, Kubernetes (K8s), and Local Agent.

The purpose of this project is to showcase best practices in CI/CD pipelines, containerization, and orchestration with Kubernetes, while leveraging Azure DevOps features like Repos, Pipelines, Boards, and Agent Pools.

🚀 Project Overview
Project Name: Calculator App

Tech Stack:

Azure DevOps for end-to-end CI/CD

Docker for containerization

Kubernetes (K8s) for deployment & scaling

Local Agent (or Microsoft-hosted Agent) for pipeline execution

Azure Boards for task and project management

Azure Repos for code version control

💡 Features Implemented
✅ CI/CD Pipeline using Azure DevOps
✅ Dockerfile to containerize the app
✅ Kubernetes Manifest Files for deploying the app to a cluster
✅ Local Agent Setup (or use Microsoft-hosted Agent via Azure DevOps)
✅ Azure Boards for project tracking
✅ Code Repositories in Azure Repos
✅ Basic Calculator functionality (add, subtract, multiply, divide)

🛠️ Project Setup & Run
Clone the repository:

bash
Copy
Edit
git clone https://github.com/your-username/calculator-app.git
Download Agent (if not uploaded here):

If you want to run the pipeline locally, download the Agent or Local Agent from Microsoft Azure DevOps:
➡️ Download Azure Pipelines Agent

Set up the Agent:

Follow the instructions to configure the Agent and connect it to your Azure DevOps organization.

Run the Pipeline:

Navigate to Azure DevOps → Pipelines → Run the pipeline.

Kubernetes Deployment:

Use the provided Kubernetes YAML files to deploy the app to a K8s cluster:

bash
Copy
Edit
kubectl apply -f k8s-deployment.yaml
kubectl apply -f k8s-service.yaml
📊 Azure DevOps Services Used
Service	Purpose
Azure Repos	Code version control
Azure Pipelines	CI/CD pipeline for building & deploying
Azure Boards	Agile project management
Azure Agent Pool	Pipeline execution (Local/Microsoft-hosted)
Azure Artifacts	(Optional) Package management

📝 Notes
Some files (like Agent files) are not uploaded to the repository due to size constraints or security concerns.

If you want to run the project locally, please ensure to set up the Agent from the Azure DevOps official guide.

This project is a learning-based demonstration and can be extended further for production use cases.

📂 Project Structure
calculator-app
│
├── index.html
├── style.css
├── script.js
├── Dockerfile

k8s
│
├── deployment.yaml
├── service.yaml

Agent/
│
├── _diag/
├── bin/
├── externals/
├── work/
├── .agent
├── .credentials
├── .credentials_rsaparams
├── config.cmd
├── reauth.cmd
├── run.cmd
└── (some files are not uploaded)

🌟 Author
Danish Kumar
GitHub: Danishkumar927
