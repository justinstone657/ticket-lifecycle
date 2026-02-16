# Active directory lab <p align="center">
<img width="1280" height="720" alt="image" src="https://github.com/user-attachments/assets/2b6f96d9-c29c-4a35-b8d0-0c4ec39cbe24" />

  - # What is Active Directory?
    Is a directory service created by Microsoft that is used to manage users, computers, and other resources on a netwwork, primarily in Windows-based enterprise environments.
    Think of it as the central brain of a corporate network that handles identity, authentication, and access control.  

<img width="1920" height="1080" alt="Client-1 and DC-1 creation in azure (step1) " src="https://github.com/user-attachments/assets/399bbebb-7ced-49c1-9f90-aa3d8cb26352" />
________________________________________________________________________________________________________________________________________________________
-  First step is setting up the Domain controller and Client-1 in Azure. 

(Have to set Domain controller's NIC Private IP address to be static and log into the VM and disable the windows firewall for testing connectivity)
________________________________________________________________________________________________________________________________________________________
<img width="1920" height="1080" alt="Disabling the firewall in DC-1 virtual machine" src="https://github.com/user-attachments/assets/7b7db585-e1a3-4f9b-8a8d-9adc057573fd" /> 
________________________________________________________________________________________________________________________________________________________
- All of the firewalls in the Domain Controller VM are disabled (for testing connectivity)
________________________________________________________________________________________________________________________________________________________
<img width="1920" height="1080" alt="Changing Client-1&#39;s DNS settings to DC-1&#39;s Private IP address" src="https://github.com/user-attachments/assets/c719cf57-c51c-4c92-9131-d74a1f1f7c24" />
________________________________________________________________________________________________________________________________________________________ 
- Changing Client-1's VM DNS settings to DC-1's Private IP Address
________________________________________________________________________________________________________________________________________________________ 
<img width="1920" height="1080" alt="Run IP config all in Client-1 VM to identify DC-1 private IP address in Client-1&#39;s DNS Servers  " src="https://github.com/user-attachments/assets/c968e398-e15a-4a6f-98d7-4e46344a800c" />
________________________________________________________________________________________________________________________________________________________ 
-  Run ipconfig /all in Client-1's VM to identify DC-1 Private IP address within Client-1's DNS servers.
________________________________________________________________________________________________________________________________________________________ 
<img width="1920" height="1080" alt="Login to DC-1 VM and install active directory domain services " src="https://github.com/user-attachments/assets/83f3c594-333b-469c-9db5-a536dc5905a8" />
________________________________________________________________________________________________________________________________________________________ 
-  Login to DC-1 VM and install active directory domain services

-  (Promoted as a DC and setup a new forest as "mydomain.com")
________________________________________________________________________________________________________________________________________________________
<img width="1921" height="1080" alt="In Active Directory users and computers ADUC I created an organizational Unit OU called EMPLOYEES and ADMINS" src="https://github.com/user-attachments/assets/b98ce029-0a87-4dd1-b26a-7552f80872cb" />
________________________________________________________________________________________________________________________________________________________ 
-  In Active Directory users and computers (ADUC), I created two organizational units (OU) called "_EMPLOYESS" and "_ADMINS".
________________________________________________________________________________________________________________________________________________________
