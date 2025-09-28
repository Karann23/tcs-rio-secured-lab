# Secured Docker Based Lab: Enforcing End-to-End Security

This repository contains the project files for the TCS iON RIO-125 internship, "Secured Docker Based Lab: Enforcing End-to-End Security".

## Project Description

This project involved designing, building, and securing a multi-container lab environment using Docker on the AWS cloud platform. The project covered the full lifecycle of a secure system: provisioning cloud infrastructure, deploying containerized applications, performing vulnerability assessments, and remediating identified security flaws.

## Key Features

- **Cloud Infrastructure:** Deployed a secure Ubuntu EC2 instance on AWS.
- **Containerization:** Built a five-service lab environment using Docker and Docker Compose, including a web server and a database.
- **Security Testing:** Performed a comprehensive security assessment using Nmap, Nessus, and Hydra.
- **Vulnerability Remediation:** Identified a critical weak password vulnerability and successfully remediated it by enforcing a strong password policy and resetting the environment.

## Technologies Used

- **Cloud:** AWS (EC2, IAM, Security Groups)
- **Containerization:** Docker, Docker Compose
- **Operating System:** Ubuntu Linux
- **Security Tools:** Nmap, Nessus, Hydra, Metasploit Framework
