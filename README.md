# Krutanic Major Project – Mithun Web App

## 📌 Project Overview

This project is a simple **Node.js web application** developed as part of my internship at **Krutanic Solutions**.
The application demonstrates how to build and deploy a web application using **Node.js, Express.js, and cloud hosting on Microsoft Azure**.

The project includes a basic web interface created with **HTML, CSS, and JavaScript**, served through an **Express server** and deployed to the cloud using **GitHub and Azure App Service**.

---

## 🌐 Live Demo

🔗 Live Website: http://mithun-webapp-e2gtgfbad9h2czbc.centralindia-01.azurewebsites.net

## 🚀 Live Application

The application is deployed on Microsoft Azure and accessible via a public URL.

Features of the deployed application:

* Simple responsive web page
* Node.js backend server
* Cloud deployment
* Continuous deployment using GitHub

---

## 🛠️ Technologies Used

**Backend**

* Node.js
* Express.js

**Frontend**

* HTML
* CSS
* JavaScript

**Cloud & DevOps**

* Microsoft Azure App Service
* GitHub
* GitHub Actions (CI/CD)

---

## 📂 Project Structure

```
Krutanic-major-project-MithunWebApp
│
├── server.js
├── package.json
├── index.html
├── style.css
└── script.js
```

---

## ⚙️ Installation and Setup

### 1️⃣ Clone the repository

```
git clone https://github.com/your-username/Krutanic-major-project-MithunWebApp.git
```

### 2️⃣ Navigate to the project folder

```
cd Krutanic-major-project-MithunWebApp
```

### 3️⃣ Install dependencies

```
npm install
```

### 4️⃣ Run the application

```
npm start
```

The server will start on:

```
http://localhost:3000
```

---

## ☁️ Deployment

The application is deployed using **Microsoft Azure App Service**.

Deployment process:

1. Created a Web App in Azure Portal
2. Connected the GitHub repository
3. Configured automatic deployment using GitHub Actions
4. Azure automatically builds and deploys the application

This setup enables **Continuous Integration and Continuous Deployment (CI/CD)**.

---

## ⚠️ Challenges Faced

During development and deployment, several issues were encountered:

### 1. Azure Default Page Display

Initially, Azure displayed a default page instead of the application.
This was resolved by properly connecting the GitHub repository through the Azure Deployment Center.

### 2. Authentication Configuration

An error occurred related to **SCM Basic Authentication being disabled**.
This was solved by selecting **User-assigned identity authentication** for deployment.

### 3. Emoji Encoding Issue

The rocket emoji displayed as incorrect characters.
This was fixed by adding UTF-8 encoding in the HTML file.

```
<meta charset="UTF-8">
```

---

## 📚 Learning Outcomes

Through this project, the following concepts were learned:

* Node.js server development
* Express.js web framework
* Static file hosting
* Cloud deployment using Azure
* CI/CD using GitHub Actions
* Debugging deployment issues

---

## 🎯 Future Improvements

Possible improvements for the project include:

* Adding a database (MongoDB or Azure SQL)
* Implementing authentication (Login/Signup)
* Creating multiple web pages
* Enhancing UI/UX with modern frameworks
* Adding API endpoints

---

## 👨‍💻 Author

**Mithun N**

Internship Project
Krutanic Solutions

---

## 📄 License

This project was developed for educational and internship purposes.
