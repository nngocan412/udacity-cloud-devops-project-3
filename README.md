# Udacity - Microservices at Scale using AWS & Kubernetes

AN NGUYEN NGOC - AnNN2

## How to run

### 1. Create images for analytics API

- Create `Dockerfile` to build python project
- Create `buildspec.yml` file to automatic push images to ECR
- Push the project to Github repo
- Create CodeBuild Pipeline to push the Github project to ECR
- Get the Image URL to used in deployment file

### 2. Configure help postgresql and deployment file

- Create EKS cluster and node group
- Add the cluster to kubectl config
- Install helm chart postgresql and seed the data in db/folder
- Create deployment file to deploy app and service
- Create db config map file and db secret file to save environment variable and database password
- Deploy these file using kubectl
