# ABC Retail Cloud Prototype

This project is a **cloud-enabled retail web application** built with **ASP.NET Core MVC** and deployed on **Azure App Service**. It demonstrates integration with multiple **Azure Storage Services** and **Azure Functions** for scalability, cost-efficiency, and cloud readiness.  


##  Features
- **Customers Table** – Adds and stores customer details in **Azure Table Storage**.  
- **Products Table + Blob Storage** – Stores product details in **Azure Table Storage** and uploads product images to **Azure Blob Storage**.  
- **Orders Queue** – Demonstrates message queuing using **Azure Queue Storage** for processing transactions.  
- **Logs** – Saves log files into **Azure File Storage**.  
- **Azure Functions Integration** – Functions are triggered to handle blob uploads, queue processing, table storage inserts, and file storage writes.  


##  Technologies Used
- ASP.NET Core MVC  
- Azure Table Storage  
- Azure Blob Storage  
- Azure Queue Storage  
- Azure File Storage  
- Azure Functions (serverless integration)  
- Azure App Service  

##  How to Run
 Clone the repository:  
   ```bash
   git clone https://github.com/your-username/abc-retail-app.git
   
*Open the project in Visual Studio 2022

*Update your appsettings.json with Azure Storage connection details

*Run the app and navigate to the Home page

Deployment

- The app is deployed on **Azure App Service** and connected to an **Azure Storage Account**.  
- Azure Functions were published and linked with the web app to handle background tasks such as blob writing and queue message handling.  
- Local testing was completed in **Visual Studio 2022**, followed by deployment using a **publish profile** (.PublishSettings).  

