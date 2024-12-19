<p align="center">
  <img src="https://miro.medium.com/v2/resize:fit:800/0*emIINniCsfbfLxbq" alt="Traffic Examination"/>  <img src="https://www.devopspertise.com/img/blog/title-azure-alerts-explore.png"/> <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQagoe7n9gFbcWj7oEwbO-Uim_6OqdQONiDeA&s"
</p>

<h1>Monitor and Log Data with Azure Monitor and Log Analytics / Create Alerts and visualize data creating dashboards.</h1>
This projects covers a centralized dashboard to monitor and manage data of created VM environments. Track the health, performance, and security of your virtual machines, troubleshoot issues, and ensure smooth operations with ease.

<h2>Environments and Technologies Used</h2>


  - Application Insights
  - Virtual Machines
  - Log Analytics Workspaces
  - Azure Monitor
  - Log Analytics Alerts
  - Dashboards
  - Dashboard data Query

<h2>Operating Systems Used</h2>

- **Windows 10 (VM on Azure)**
  

<h2>High-Level Steps</h2>

1. **Create VM machine in Azure**  



https://github.com/user-attachments/assets/b57cb825-dbdd-45ee-9c01-99518728ae87






2. **Enable Azure Monitor**  
  


https://github.com/user-attachments/assets/41933b8a-c4d2-4aca-af22-5175a039cf4f



3. **Enable Log Analytics**
   
  I. In the Azure Portal, search for Log Analytics Workspaces.
  
II. Click Create and provide the following:

     Name: Enter a name (e.g., MyLogAnalyticsWorkspace).
     Region: Select the same region as your VM.
     Resource Group: Choose the resource group of your VM.

After creation, navigate to the workspace and note its Workspace ID and Key.

https://github.com/user-attachments/assets/d3f0bb35-1eac-4830-8e6e-36ca6998d1b2



4. **Configure Alerts**

NOTE: You can also set up recommended alert rules which will advise best practices to avoid data loss as well as generate an alert which you will be notified either via email or SMS.

https://github.com/user-attachments/assets/f82099e0-90de-4aef-a090-1b7a8f5af65e

With this alert created you will receive messages and email notifications with log information. One example of this can be for a VM stopped for the client as shown below:

![image](https://github.com/user-attachments/assets/46ba5bc7-ac25-4abc-92e0-86c8e69dcd8f)



5.  **Build a Custom Dashboard with Queries and Metrics to determine best practices to improve Virtual Machines.**
   
   You can download the results of the total query as CSV for further reference. In a query where there is a lot of data to be fulfilled across multiple periods of time, a chart can be generated from the dashboard. In this case, all the alerts created needed more data in order to process a chart. Metrics can be shown for overall usage of VM as well as Alerts and Log Analytics workspaces created by creating a custom dashboard, allowing you to monitor performance, usage and use.



https://github.com/user-attachments/assets/bfa402cf-27af-4b10-8d98-5d4e23cb11e1



6. **Link VM to Log Analytics Workspace (Optional)**
   
NOTE: This approach is used to showcase how it used to work to create log analytics with the VM/RG. Currently is deprecated.

https://github.com/user-attachments/assets/68ea7f7b-3e34-4970-a865-41035e1d5bdf
<h2>Actions and Observations</h2>

<p>
  With this tutorial you will be able to set up an Azure resource monitoring solution to track metrics and logs for a virtual machine (VM).
</p>

<h2>Conclusion</h2>
This demonstration illustrates a no-code monitoring and logging solution for your Azure VM, complete with performance insights, log aggregation, and real-time alerts, all accessible via a centralized dashboard.
