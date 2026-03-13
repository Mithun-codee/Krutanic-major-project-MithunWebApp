# ☁️ Azure Web Application Deployment
### Cloud Computing Internship Project – Krutanic Solutions

![Azure](https://img.shields.io/badge/Cloud-Microsoft%20Azure-blue)
![Node.js](https://img.shields.io/badge/Backend-Node.js-green)
![GitHub](https://img.shields.io/badge/CI/CD-GitHub%20Actions-black)
![Status](https://img.shields.io/badge/Deployment-Live-success)

---

# 📌 Project Overview

This project demonstrates how to deploy and manage a scalable web application on **Microsoft Azure (Free Tier)**.

The application is hosted using **Azure App Service**, connected to **Azure SQL Database**, and monitored using **Azure Application Insights**.

The project also integrates **GitHub Actions for Continuous Integration and Continuous Deployment (CI/CD)**.

This project was completed as part of my **Cloud Computing Internship at Krutanic Solutions**.

---

# 🌍 Live Application

🔗 **Website URL**

https://mithun-webapp-e2gtgfbad9h2czbc.centralindia-01.azurewebsites.net

The application is publicly accessible and deployed on **Azure App Service**.

---

# 🧰 Technologies Used

## Frontend
- HTML5
- CSS3
- JavaScript

## Backend
- Node.js

## Cloud Platform
- Microsoft Azure

## DevOps Tools
- GitHub
- GitHub Actions

---

# ☁️ Azure Services Used

| Service | Purpose |
|-------|-------|
| Azure App Service | Hosting the web application |
| Azure SQL Database | Cloud database for storing data |
| Azure Resource Groups | Organizing cloud resources |
| Application Insights | Monitoring and logging |
| GitHub Actions | Automated deployment |

---

# 🏗 Cloud Architecture

```
User Browser
      │
      ▼
Azure App Service (Web App Hosting)
      │
      ▼
Azure SQL Database (Cloud Data Storage)
      │
      ▼
Application Insights (Monitoring & Analytics)
```

---

# 📂 Project Structure

```
azure-webapp-project
│
├── index.html
├── style.css
└── script.js
│
├── server.js
├── package.json
│
├── .github/workflows
│   └── azure-deploy.yml
│
└── README.md
```

---

# 🗄 Database Configuration

The application connects to **Azure SQL Database**.

Example SQL table used:

```sql
CREATE TABLE Users (
    id INT IDENTITY(1,1) PRIMARY KEY,
    name VARCHAR(50),
    email VARCHAR(100)
);
```

---

# ⚙️ Deployment Process

The application uses a **CI/CD pipeline with GitHub Actions**.

### Deployment Steps

1. Create Azure Resource Group  
2. Create Azure App Service (Free Tier F1)  
3. Create Azure SQL Database  
4. Push code to GitHub repository  
5. Configure GitHub Actions workflow  
6. Deploy automatically to Azure Web App  

Every push to the **main branch** triggers **automatic deployment**.

---

# 📊 Monitoring

The application is monitored using **Azure Application Insights**.

Monitoring features include:

- Performance metrics
- Error tracking
- Request logging
- Live traffic monitoring

---

# 🎯 Learning Outcomes

Through this project, I learned:

- Cloud application deployment
- Azure App Service configuration
- Azure SQL Database integration
- CI/CD pipeline implementation
- Cloud monitoring using Application Insights
- GitHub integration with Azure

---

# 👨‍💻 Author

**Mithun N**  
Cloud Computing Intern  
Krutanic Solutions

---

# 📜 License

This project is created for **educational and internship purposes**.
