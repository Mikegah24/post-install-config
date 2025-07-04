<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

# post-install-config

Admin/Analyst Login Page:
http://localhost/osTicket/scp/login.php 

End Users osTicket URL:
http://localhost/osTicket 

### Acknowledge Agent Panel vs Admin Panel

- Agent Panel
![image](https://github.com/user-attachments/assets/9eb26551-60cc-4d43-b3bc-1d5f0d0f7e6c)


- Admin Panel

![image](https://github.com/user-attachments/assets/a76e312c-72c2-4983-8e5b-19e71a387842)



Configure Roles (for grouping permissions)
Admin Panel -> Agents -> Roles
  - Supreme Admin
![image](https://github.com/user-attachments/assets/066088cf-dbfc-4512-a802-74f603200504)
![image](https://github.com/user-attachments/assets/aaf0b38f-47c7-4ace-a456-76d11b3d7c36)
![image](https://github.com/user-attachments/assets/86578d13-b996-481b-a099-5adc2bc21db1)


Configure Departments (Ticket Visibility, Help Desk vs SysAdmins, vs Networking)
Admin Panel -> Agents -> Departments
  - SysAdmins
![image](https://github.com/user-attachments/assets/28591267-0290-427d-9160-1fed563288d7)
![image](https://github.com/user-attachments/assets/ba78ea64-e8ef-4aba-8f00-cea6ab08ce6b)
![image](https://github.com/user-attachments/assets/eab58703-c075-442c-9ebf-8001aaf903cc)


Configure Teams
Admin Panel -> Agents -> Teams (Pull Agents from different Departments)
  - Online Banking

Allow anyone to create tickets
Admin Panel -> Settings -> User Settings (UNCHECK: unregistered users can create tickets)
  - Registration Required: Require registration and login to create tickets

![image](https://github.com/user-attachments/assets/55a62c86-6447-4768-af5b-035a5d8ce32f)


Configure Agents (workers)
Admin Panel -> Agents -> Add New
    - Jane (Dept: SysAdmins)
    - John (Dept: Support)

- Jane
![image](https://github.com/user-attachments/assets/14bd192d-8ee2-4fc8-9adb-5483397ae137)
![image](https://github.com/user-attachments/assets/20abe5b8-1cef-47e8-bbe9-2446fbd9c0f6)
![image](https://github.com/user-attachments/assets/4818587a-46ca-4491-a7db-c3eac7f9b625)


Configure Users (customers)
Agent Panel -> Users -> Add New
  - Karen
  - Ken
![image](https://github.com/user-attachments/assets/69a25665-bc2d-4278-86f7-c12a7a31533f)
![image](https://github.com/user-attachments/assets/953e6440-e5e7-4392-b292-b68e1f2d51fa)


Configure SLA
Admin Panel -> Manage -> SLA
  - Sev-A (Grace Period: 1 hour, Schedule: 24/7)
  - Sev-B (Grace Period: 4 hours, Schedule: 24/7)
  - Sev-C (Grace Period: 8 hours, Business Hours)
![image](https://github.com/user-attachments/assets/1fa6e1ed-bf4a-48c1-a925-6fbcfec7356f)
![image](https://github.com/user-attachments/assets/6543be7a-751f-44f0-9c4e-5fcdce4882d9)
![image](https://github.com/user-attachments/assets/eb82a564-3b1e-43a0-af89-06127848a833)
![image](https://github.com/user-attachments/assets/5fc2bb71-29d7-4714-8eb3-865e33ecf918)

Configure Help Topics (For when users create a ticket)
Admin Panel -> Manage -> Help Topics
  - Business Critical Outage
  - Personal Computer Issues
  - Equipment Request(General Iquiry)
  - Password Reset
  - Other

![image](https://github.com/user-attachments/assets/6ec6be4f-d65b-4304-b25e-9e9d33f9d5df)
![image](https://github.com/user-attachments/assets/a6e9a73c-f9cb-44e8-84ba-31a2b014b1ff)
![image](https://github.com/user-attachments/assets/a37d52b1-8528-41ec-b3eb-ee442b3b321e)


