**Overview**

- This project demonstrates how to build a Jenkins-powered CI/CD pipeline on AWS.  
- It integrates:
  - **GitHub** for source control  
  - **Jenkins** for continuous integration and delivery  
  - **Ansible** for automated deployment  
  - **Docker** for containerized application hosting  
- The architecture uses **two AWS EC2 instances**:
  - One for hosting both **Jenkins and Ansible**
  - Another dedicated as a **Docker server**
- This setup ensures modularity, streamlined automation, and a clean separation between orchestration and runtime environments.



<img width="912" height="343" alt="Jenkins-Ansible-Docker" src="https://github.com/user-attachments/assets/1e0fcbe3-9304-4e5a-9621-0ef21fa2f249" />
