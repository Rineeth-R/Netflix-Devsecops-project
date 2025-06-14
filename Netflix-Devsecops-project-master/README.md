**DevSecOps Project - Netflix Clone on cloud using Jenkins**

![Screenshot 2025-06-14 094417](https://github.com/user-attachments/assets/9385b9aa-cbe9-4731-b748-4883dd96ef5c)


**Project Overview:**

Developed and deployed a Netflix-like streaming application on AWS using DevSecOps best practices. 

Implemented a CI/CD pipeline with Jenkins, integrated security tools (SonarQube, Trivy, OWASP Dependency-Check),
and set up monitoring with Prometheus and Grafana. Automated containerized deployments using Docker and Kubernetes.

**Key Responsibilities & Technologies Used**

**1. Cloud Infrastructure Setup & Deployment (AWS & Docker)** 

Provisioned AWS EC2 instance (Ubuntu 22.04) for hosting the application.
Installed and configured Docker for containerized deployment.
Built and deployed the application as a Docker container:
Pulled the application source code from GitHub.
Built Docker images and ran the application using Docker Compose.
Integrated TMDB API Key for fetching movie details.

**2. Security Implementation (DevSecOps)**
Installed and configured SonarQube to perform static code analysis for security vulnerabilities.
Scanned application dependencies using OWASP Dependency-Check.
Used Trivy for container image scanning to identify vulnerabilities.
Implemented SonarQube Quality Gate in Jenkins pipeline to enforce security standards.

**3. CI/CD Pipeline Automation (Jenkins)**

Installed Jenkins on the AWS EC2 instance.
Configured a Jenkins declarative pipeline for automating build, security scans, and deployment.
Integrated Docker plugins, Node.js, and Java (JDK 17) in Jenkins for seamless execution.
Implemented DockerHub authentication in Jenkins to push Docker images securely.
Configured Jenkins to trigger builds automatically on code commits.

**4. Monitoring & Logging (Prometheus & Grafana)**

Installed and configured Prometheus to monitor application performance.
Deployed Node Exporter for collecting system metrics.
Integrated Grafana to visualize logs and metrics from Prometheus.
Configured Prometheus monitoring for Jenkins CI/CD pipeline performance tracking.

**5. Kubernetes Deployment & Scaling**

Created a Kubernetes cluster with node groups for auto-scaling.
Deployed application containers in Kubernetes Pods for high availability.
Configured Helm to install Prometheus and monitor Kubernetes nodes.

**6. Notification & Alerts**

Set up email notifications in Jenkins for build failures.
Configured Prometheus AlertManager to notify on system anomalies.

**Key Achievements**

 A) Successfully deployed a Netflix Clone on AWS with an automated CI/CD pipeline.

 B) Implemented shift-left security by integrating SonarQube, Trivy, and OWASP Dependency-Check.

 C) Achieved 100% automation for build, security, and deployment using Jenkins.

 D) Improved system observability with real-time monitoring dashboards using Grafana.

 E) Ensured secure Docker image storage by integrating DockerHub authentication.

 F) Scaled application seamlessly using Kubernetes with Node Groups.


**Technical Stack & Tools**

**Cloud Platforms:** AWS

**CI/CD:** Jenkins, Git, GitHub Webhooks

**Containerization:** Docker, DockerHub, Kubernetes, Helm

**Security Tools:** SonarQube, OWASP Dependency-Check, Trivy

**Observebility - Monitoring & Logging:** Prometheus, Grafana, Node Exporter

**Programming & Scripting:** Shell Scripting, JavaScript, Node.js

**Database & APIs:** TMDB API

**Jenkins passed :-**

![Screenshot 2025-02-27 213928](https://github.com/user-attachments/assets/3adb6a13-9eae-4c4d-a639-12e760f62367)

![Screenshot 2025-02-27 214128](https://github.com/user-attachments/assets/45fc4aec-40c3-40c6-b2c8-b798e7dd9041)



**SonarQube passed :-**

![Screenshot 2025-02-27 214858](https://github.com/user-attachments/assets/e46175d7-d986-4e5e-8654-c7941bdbd52f)




**ARGOCD SYNCED :-**

![Screenshot 2025-02-27 214731](https://github.com/user-attachments/assets/3f797d58-7d46-4570-9d81-5bb55c0c3890)




**PROMETHEUS :-**

![Screenshot 2025-02-27 215224](https://github.com/user-attachments/assets/75e05b9d-8c12-48ab-85ae-8aeb3d356b7b)


**NETFLIX PAGE :-**

![Screenshot 2025-02-27 215057](https://github.com/user-attachments/assets/02d4b44c-8928-4bc4-ae80-48ce7cc15d4e)


