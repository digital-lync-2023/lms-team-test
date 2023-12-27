# LMS-JAVA MINIKUBE DEPLOYMENT
## STEPS:
- Launch Server
- Install Software
- Create K8S Manifest files
- Deploy K8S files

## STEP-1: Launch Server
- Guide - https://minikube.sigs.k8s.io/docs/start/
- Requirements —-------t2.medium instance in AWS
- 2 CPUs or more
- 2GB of free ram memory
- 30GB of free disk space

## STEP-2: Install Softwares
- docker
- kubectl
- minikube

## STEP-3: Create K8S Manifest files
### database 
- write and apply mysql-secret.yml
- write and apply mysql-deployment.yml
- write and apply mysql-cluster-ip.yml
### Backend:
- write and apply backend-configmap.yml
- write and apply backend-deployment.yml
- write and apply backend-service.yml
### Frontend:
- write and apply frontend-deployment.yml
- write and apply frontend-service.yml
