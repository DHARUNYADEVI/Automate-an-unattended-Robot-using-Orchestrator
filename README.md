# Automate-an-unattended-Robot-using-Orchestrator
## NAME:Dharunyadevi S
## Register number:212223220018
## AIM:
To automate and execute an unattended Robot in UiPath Orchestrator by publishing a project from UiPath Studio, creating necessary assets and triggers, and running the process remotely.

## ALGORITHM:
### Step 1: 
Create and Publish a Project Open UiPath Studio and create a sample project (e.g., a Message Box or any automation). Save the project and click "Publish" to upload it to Orchestrator (Tenant Processes Feed).
### Step 2: 
Log in to UiPath Orchestrator
Go to https://cloud.uipath.com and log in. Choose your Orchestrator tenant.
### Step 3:
Provision Robot and Machine Go to Tenant > Machines: Add a Standard Machine with the same name as your device (check in Studio via Help > License Details). Under Tenant > Folders > Manage Access, ensure your user is assigned with proper roles (e.g., Robot role). Go to Tenant > Robots and create a Unattended Robot: Link it to the correct machine and user. Assign it to your folder.
### Step 4: 
Create Process in Orchestrator
In Automation > Processes, click Add Process. Select the published package from the dropdown. Choose version, folder, and display name. Click Create.
### Step 5:
Create Trigger to Schedule the Robot Go to Automation > Triggers. Click Add Trigger: Select your process. Set Trigger Type to Time. Choose the time, frequency (Once, Daily, etc.). Click Create.
### Step 6:
Monitor Execution In Jobs, you can monitor the status (Pending, Running, Success, Faulted). View logs, time stamps, and robot execution details.

## PROGRAM:
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/3594f10d-264d-44c3-86d1-dfd7dcdf70b1" />

<img width="776" height="654" alt="image" src="https://github.com/user-attachments/assets/4ec32d33-1756-4e50-ab84-ae494d2a4028" />


<img width="1277" height="1079" alt="Screenshot 2025-11-10 212637" src="https://github.com/user-attachments/assets/144530b9-7aa1-4440-b490-8f9c87025f24" />

<img width="1920" height="1080" alt="Screenshot (483)" src="https://github.com/user-attachments/assets/8b76e641-1456-48a7-90ca-e75eb2f18b28" />

<img width="1920" height="1080" alt="Screenshot (484)" src="https://github.com/user-attachments/assets/25216235-ab1a-45b9-a572-01405a83f02d" />

<img width="1920" height="1080" alt="Screenshot (485)" src="https://github.com/user-attachments/assets/1d1c7a1b-8e6e-4a29-bb76-8475824d51c7" />

<img width="1920" height="1080" alt="Screenshot (486)" src="https://github.com/user-attachments/assets/c0560d4c-ae4a-4936-88e8-d561907ea7ab" />


<img width="1920" height="1080" alt="Screenshot (489)" src="https://github.com/user-attachments/assets/528550c1-76e9-4eb5-90d6-a90736a56108" />

<img width="1920" height="1080" alt="Screenshot (492)" src="https://github.com/user-attachments/assets/2af8a2a2-4cb9-42e7-beda-ba7608cebcc0" />

<img width="1920" height="1080" alt="Screenshot (494)" src="https://github.com/user-attachments/assets/c22c9500-8704-4499-afc3-e083ff10de09" />

## OUTPUT:

<img width="1920" height="1080" alt="Screenshot (485)" src="https://github.com/user-attachments/assets/c7c0779d-de0f-4419-943d-c3c7c0a6667e" />

<img width="219" height="182" alt="image" src="https://github.com/user-attachments/assets/fa2b1072-f920-4f46-8864-17dbcd1b4c24" />

## RESULT:
The automation process was successfully published, triggered, and executed as an unattended job using UiPath Orchestrator. This setup ensures automation can run without human presence at scheduled times.
