### Project Session
--------------------
Agenda:
- Project Explain
- Project Handson

Project
-------
DevOps OPS (Support)

Project Development - DYL (CRM) - 3.6 Years
SDLC - req, plan, design, code, test, deploy, monitoring
- repository create, access, authentication
- Branching strategy, 
- Dev environemnt
- Test env
- Infra Best practices
- console, iac
- automation

Description:
CRM, dyl.com, DYL
Team Size: 13 (3FD, 3BD, 2T, 2FE, 1SE, 1DE, 1PM)
DevOps (sprints 3 Week, Sprint Review meet(client))

Tech Stack:
Frontend-5 (Angular framework, html, css, js, node)
Bankend-18 (Springboot framework, maven, java)
DB-18 (postgres)

Infrastructure:
hybrid - Serverless Hosting + Containerization + Servers
AWS stack
s3 - eks - rds

Deployment Strategy / Branching Strategy:
Feature
DEV -----
TEST ----
UAT -----
PROD ----
hotfix

DevOps Tools: CICD Jenkins, IAC Terraform, Monitoring Datadog, SCM Git Github,
Build Maven, QA Sonarqube, Containerization Docker, Orchestration K8s

Pipeline: 
(webhook)PULL-BUILD-TEST-DEPLOY
github-maven-sonarqube-(docker image, push, kubectl apply -f)

Responsibilities:
- Create and Manage repo
- repo access
- manage branches
- implement branching strategy
- manage keys and tokens 
- jenkins server setup
- plugins manage
- pipeline wrote
- take backup of jenkins server
- trigger 
- trigger automate webhook
- jenkins acess manage
- infra design
- write terraform code
- tfstate secure and manage
- terraform modules
- create dashboard
- manage agents 
- monitor and alert incidents
- Install and manage maven version
- integrate maven with pipeline
- manage POM.xml
- create sonarqube server
- creat qulity gate
- integrate sonarqube with pipeline
- create webhook for quality gate
- dockerfile
- docker image
- image optimization
- manage docker registry
- write manifest for deployment, hpa, ingress, service
- manage k8s cluster EKS
- troubleshoor networking and high resource utilization issues
- plan deployment strategies



### Project Handson

#### Prequisites

GitHub Account, AWS Account, Jenkins Server, Sonarqube Server, Maven, Terraform, Kubectl, Docker, awscli, git

#### Design
S3 - EKS - RDS - draw.io

#### Coding
Terraform: https://github.com/shubhamkalsait/cbz-three-tier-infra.git
Source-Code: https://github.com/cloud-blitz/angular-java
frontend: https://github.com/shubhamkalsait/b19-frontend.git
backend: https://github.com/shubhamkalsait/b19-backend.git

#### DB Credentials
DB_HOST: terraform-20250104105920323600000006.c5eiukqyws07.us-east-2.rds.amazonaws.com
DB_NAME: springbackend
DB_PORT: 3306
DB_USER: admin
DB_PASS: Redhat123