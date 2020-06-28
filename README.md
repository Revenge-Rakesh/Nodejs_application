#Node Js Application Deployment Using kubernetes

- deploy-nodejs.yml file is the main file which will deploy nodejs application with customized image.
- Image is created on Amazon ECR.
- nodejs-hpa.yml file used for auto scaling of nodejs application with minimum of 7 and maximum of 10
  replicasets.
- all.yml file used to take the user inputs like docker user name / ECR registry username
  user password. 
- For security purpose, it is better to create different file without exposing out side


Basics Required:
----------------
1. Kubernetes
2. Docker
3. AWS 
4. Ansible
5. Node Js
