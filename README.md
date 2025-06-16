# 👋 Hello, I'm Sri Vignesh K.V.

🎓 Mechanical Engineering Graduate | 🛠️ Cloud DevOps Intern @ Abhyaz  
🚀 Passionate about Cloud Infrastructure, Automation & Continuous Delivery

I'm focused on building robust CI/CD pipelines, working with AWS, Docker, Jenkins, and modern DevOps tooling to deploy and scale applications.  
I believe in continuous learning and love solving real-world engineering problems with automation and cloud-native technologies.

---

## 🧰 Tech Stack & Tools

![AWS](https://img.shields.io/badge/AWS-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=for-the-badge&logo=jenkins&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

---

## 🌟 Featured Projects

<details>
<summary>🔁 CI/CD Pipeline for Node.js App (Medusa)</summary>

A complete CI/CD workflow using **Jenkins**, **Docker**, and **AWS EC2** to automate build, test, and deployment of a Node.js application.

- ✅ Built custom Jenkins pipeline
- ✅ Containerized the app with Docker
- ✅ Hosted on Amazon EC2

🔗 [GitHub Repo](https://github.com/srivigneshkv14/medusa-application)

</details>

<details>
<summary>🤖 Invoice Automation with Zoho Flow</summary>

Automated invoice generation and email notifications using **Zoho Books** and **Zoho Flow** integration.

- 📩 Invoice created in Zoho Books triggers email
- 🔁 Integrated using Zoho Flow custom workflows

</details>

---

## 📊 CI/CD Pipeline Flow (Medusa)

```mermaid
graph TD
  A[Push Code to GitHub] --> B[Jenkins Triggered]
  B --> C[Docker Build]
  C --> D[Push to DockerHub]
  D --> E[Deploy to AWS EC2]
