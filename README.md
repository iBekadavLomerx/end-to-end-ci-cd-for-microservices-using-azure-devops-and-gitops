<h1>End-to-End CI/CD for Microservices using Azure DevOps & GitOps </h1>

<h2>Description</h2>
Designed and implemented a complete CI/CD pipeline for a multi-tier, multi-microservice application built with Python, .NET, and Java, using Redis for caching and MySQL for storage. Automated builds and deployments with Azure DevOps Pipelines, containerized services with Docker, deployed to AKS, and implemented GitOps workflows with Argo CD for reliable, version-controlled deployments. Ensured faster releases and reliable deployments for multi-service applications.

<h2>Tools and Technologies</h2>

- Azure DevOps
- GitOps
- Argo CD
- AKS (Azure Kubernetes Service)
- Docker
- Python, .NET, Java
- Redis
- MySQL

<h2>Project Walk-through</h2>

<p align="center">
1. Migrated multi-microservice repository from GitHub to Azure Repos for centralized version control<br />
<img src="https://i.postimg.cc/pTkcLJh2/1.jpg"/>
<br />
<br />
2. Configured Azure Container Registry (ACR) for centralized image storage and versioning <br/>
<img src="https://i.postimg.cc/C1dkbGrM/2.jpg" />
<br />
<br />
3. Created CI pipelines in Azure DevOps to automate Docker image builds, push to ACR, and update Kubernetes manifests with new tags<br/>
<img src="https://i.postimg.cc/QtRWhzgL/3.jpg"/>
<br />
<br />
4. Provisioned and configured Azure Kubernetes Service (AKS) for microservice deployments <br/>
<img src="https://i.postimg.cc/JnGMP4km/5.jpg" />
<br />
<br />
5. Implemented GitOps workflows with Argo CD for automated, version-controlled deployments from Git to AKS <br/>
<img src="https://i.postimg.cc/tCsmrnJY/4.jpg" />
<br />
<br />

</p>

<h2>Special Thanks</h2>

- https://github.com/dockersamples/example-voting-app
- Abhishek Veeramalla
