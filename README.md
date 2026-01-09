# Azure Web App Service – Blazor Web Application

![Azure](https://img.shields.io/badge/Azure-Cloud-blue?logo=azure)
![Blazor](https://img.shields.io/badge/Blazor-.NET%208-purple?logo=dotnet)
![GitHub](https://img.shields.io/badge/GitHub-Repo-black?logo=github)
![License: MIT](https://img.shields.io/badge/License-MIT-green)
![CI/CD Ready](https://img.shields.io/badge/CI%2FCD-GitHub%20Actions%20%7C%20Azure%20Pipelines-orange)

This project demonstrates how to build, publish, and deploy a **Blazor Web Application** to **Azure App Service (Windows)** using **Visual Studio**, and then push the source code to **GitHub** with proper repository setup.

---

## 🛠️ Prerequisites
- Azure Subscription  
- GitHub Account  
- Azure VM (Windows)  
- Visual Studio (Latest)  
- Git installed  
- Stable Internet Connection  

---

## ☁️ Infrastructure Setup
1. **Create Azure Virtual Machine**
   - OS: Windows Server 2025  
   - VM Size: DS2_v2  
   - RAM: 8 GB  
   - Disk: SSD – 256 GB  
   - Access: RDP  

---

## 💻 Application Development
2. **Install Visual Studio**
   - Download and install Visual Studio (Latest Version)  
   - Select workloads:  
     - ASP.NET and web development  
     - .NET desktop development  

3. **Create Blazor Web Application**
   - Open Visual Studio  
   - Click *Create a new project*  
   - Select *Blazor Web App*  
   - Choose framework (.NET 8 / latest)  
   - Configure project name and location  

4. **Build and Run Application**
   - Click *Build*  
   - Click *Run*  
   - Verify the application runs locally without errors  

---

## 🚀 Deploy to Azure App Service
5. **Publish Application**
   - Right-click project → *Publish*  
   - Select *Azure*  
   - Choose *Azure App Service (Windows)*  

6. **Create Publish Profile**
   - Sign in using Azure Username and Password  
   - Select:  
     - Subscription  
     - Resource Group  

7. **Create Azure Web App**
   - App Service Type: Windows Web App  
   - App Service Plan: S1  
   - Estimated Usage: ~70 hours  

8. **Publish Application**
   - Click *Publish*  
   - Wait for deployment to complete successfully  

9. **Verify Deployment**
   - Copy the Web App URL  
   - Paste it into a browser  
   - Confirm the application is live and accessible  

---

## 📦 Source Control – GitHub
10. **Push Code to GitHub**
   - Repository Configuration:  
     - Visibility: Public  
     - License: MIT  
     - Include: README.md  

   - Git Commands:
     ```bash
     git init
     git add .
     git commit -m "Initial commit - Blazor Web App deployed to Azure"
     git branch -M main
     git remote add origin https://github.com/<username>/<repo-name>.git
     git push -u origin main
     ```

---

## 📄 License
This project is licensed under the **MIT License**.

---

## ✅ Outcome
- Blazor Web App deployed on Azure App Service  
- Public GitHub repository with clean documentation  
- Ready for CI/CD integration (Azure Pipelines / GitHub Actions)  

---

## 📌 Author
**Atul Kamble**  
Cloud & DevOps Trainer | Azure & AWS Architect  
Founder – Cloudnautic  
