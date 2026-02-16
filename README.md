# Final-Project-HTU-DevOps



This is the final project for the HTU DevOps track

the documentation file showcases the four scenarios.



### Scenario 1 : Enterprise Linux Infrastructure Rebuild (RHEL 9)  :



* Rebuilt a RHEL 9.7 enterprise environment from scratch including LVM storage, departmental isolation (3770 permissions), automated backups, and system optimization with Tuned.
* Implemented secure SSH hardening with key-based authentication and disabled password login.
* Deployed an Apache HR placeholder app with SELinux policies, firewall rules, and custom port configuration.
* Automated user/group provisioning and enforced structured access control.



### Scenario 2 : Scalable AWS Backend Architecture – HTU Schedemy :



* Deployed Spring Boot backend on AWS EC2 with systemd service configuration.
* Designed a scalable architecture using Application Load Balancer + Auto Scaling Group (2–4 instances).
* Implemented HTTPS with ACM, Route 53, and CloudFront for secure global access.
* Built CloudWatch dashboards monitoring traffic, performance, and infrastructure health.



### Scenario 3 : CI/CD Pipeline with GitHub Actions \& Ansible :



* Designed a full CI/CD pipeline triggered on main branch merges.
* Automated EC2 provisioning using Ansible and AWS CLI.
* Created dynamic AMI generation and automatic Launch Template updates.
* Implemented zero-downtime deployment via Auto Scaling Group instance refresh.



### Scenario 4 : Dockerized PixelFed Deployment on AWS :



* Deployed a containerized PixelFed photo-sharing app using Docker \& Docker Compose.
* Configured production environment variables and persistent services.
* Managed EC2 provisioning, security groups, and application exposure.
* Automated container lifecycle and admin setup.
