# MyIISApp - Automated Deployment to IIS using Azure DevOps

## ✅ Project Status

- Source code hosted on GitHub ✅
- CI pipeline set up in Azure DevOps ✅
- Azure Environment created for IIS deployment ✅
- Azure VM created and ready for deployment ✅
- - **CD (Release) pipeline pending** due to student subscription issue 


## 🛠️ Technologies Used
- .NET Framework
- Azure DevOps (CI/CD)
- Windows IIS Server
- GitHub for source control


## 🔗 Azure DevOps Project
> Azure DevOps project: MyIISApp  
> Pipelines connected to this GitHub repo


**Create a virtual machine:**

<img width="940" height="529" alt="image" src="https://github.com/user-attachments/assets/d56df7da-881d-4133-b01a-0f1dc8d6bd6c" />


<img width="1919" height="913" alt="image" src="https://github.com/user-attachments/assets/b1add36b-895f-4875-a6c0-497ba1096aad" />


**Application Deployed**

<img width="940" height="450" alt="image" src="https://github.com/user-attachments/assets/5b8d5b78-f15b-4aac-8b4a-6ab0a3fd222a" />


**Author**

Name: Purva S. Sonaje

Email: purvasonaje.arcade@gmail.com

LinkedIn: linkedin.com/in/purva-sonaje-ab4052288



📖 Project Description
MyIISApp is a sample .NET application that demonstrates how to automate the deployment of web applications to a Windows IIS Server using Azure DevOps. It uses Continuous Integration (CI) to build the project and prepares for Continuous Deployment (CD) once the Azure subscription is upgraded.

This project showcases how to streamline deployment workflows using DevOps practices, Azure infrastructure, and IIS hosting.

🎯 Objectives
Automate the build and deployment pipeline using Azure DevOps.

Host the .NET application on a Windows Virtual Machine with IIS enabled.

Ensure secure and scalable deployment using GitHub-Azure integration.

Provide hands-on experience with CI/CD and cloud infrastructure.

🧱 Project Architecture
plaintext
Copy
Edit
GitHub (Source Code)
       ↓
Azure DevOps CI Pipeline
       ↓
Azure VM (Windows Server with IIS)
       ↓
Manual Deployment (Temporary) ➜ Future: Azure DevOps CD Pipeline
🚧 Prerequisites
Before running or contributing to this project, ensure the following are in place:

Azure DevOps Account

GitHub Repository

Azure Subscription (with permissions to create VM & resources)

Windows Virtual Machine (IIS Installed)

.NET Framework development environment (for local testing)

🧪 Testing & Validation
After deployment, the application was tested on the IIS server using the public IP of the Azure VM.

Verified that the build artifacts were generated correctly through the CI pipeline.

Application is accessible through the browser confirming a successful deployment.

📷 Screenshots
Step	Description	Screenshot
1	Azure VM creation with IIS	
2	Azure environment running	
3	Application deployed successfully	

📦 Folder Structure (Optional)
plaintext
Copy
Edit
MyIISApp/
│
├── src/                     # Application source code
│   └── MyIISApp.sln         # .NET Solution File
│
├── azure-pipelines.yml     # CI pipeline configuration
├── README.md               # Project documentation
├── .gitignore
└── LICENSE (if any)
🙋‍♀️ How to Contribute
Fork this repository

Create a feature branch (git checkout -b feature-name)

Commit your changes (git commit -m "Added new feature")

Push to the branch (git push origin feature-name)

Open a Pull Request

📅 Timeline (Milestone Tracking)
Task	Status	Date
GitHub repo created	✅	[Date]
CI pipeline created	✅	[Date]
Azure VM configured	✅	[Date]
IIS deployed	✅	[Date]
CD pipeline setup	🔄 Pending	Planned

📄 License
This project is for academic/demo purposes only. You may fork and modify it for learning purposes.
