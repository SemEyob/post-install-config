


# osTicket - Post-Install Configuration

![osTicket logo](https://i.imgur.com/Clzj7Xs.png)

This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.

## Key Takeaways and Skills Developed

### **Technical Skills:**
- **System Administration:** Learned how to configure system roles, departments, and teams to streamline IT operations.
- **User Management:** Gained experience adding and managing users, a key responsibility in IT helpdesk environments.
- **Service Level Agreements (SLA):** Developed an understanding of setting up and applying SLA policies for ticket prioritization.
- **Helpdesk Ticketing Workflow:** Practiced configuring help topics and permissions, ensuring smooth ticket management.

### **Problem-Solving Skills:**
- **Issue Prioritization:** Understanding ticket management policies helps with effectively troubleshooting and resolving IT issues.
- **Team Collaboration:** Learned how to assign agents and create specialized teams for improved service response.

### **Professional Skills:**
- **Customer Service Orientation:** Setting user roles and ticket permissions highlights how IT professionals can improve customer interactions.
- **Documentation and Reporting:** Familiarity with detailed system configuration fosters better system documentation and reporting practices.


In this project, I configured osTicket by managing user roles, departments, and ticket settings. I set up roles to group permissions, defined departments for ticket visibility, and created teams by combining agents from different departments. I required user registration before ticket creation, added agents and users, and set up SLAs for different severity levels. Additionally, I created help topics to categorize tickets. This hands-on experience helped me learn to manage user roles, workflows, and settings in a ticketing system to improve help desk efficiency.


## Environments and Technologies Used
- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

## Operating Systems Used
- Windows 10 (21H2)

## Post-Install Configuration Objectives
- Configuring Roles
- Configuring Departments
- Configuring Teams
- Ticket Permission
- Configuring Agents
- Adding New Users
- Configuring SLA's (Service Level Agreements)
- Creating Help Topics

## Configuration Steps

### 1) Configuring Roles
Login to your Admin account using this link: `http://localhost/osTicket/scp/login.php`. Switch to the **Admin Panel** and navigate to **Agents -> Roles** to create and manage roles. Then create a **"Supreme Admin"** role.

![Capture4](https://github.com/user-attachments/assets/dd2138d1-4b9f-4de2-8d8e-f80f112f195d)








### 2) Configuring Departments
Go to **Agents -> Departments** and click **Add New Department**. Fill in the relevant department information to create a **SysAdmins** department and click **Add Dept**.

![Capture6](https://github.com/user-attachments/assets/8fe29b7d-ba72-4483-835a-44728a9cb566)

![Department Details](https://i.imgur.com/4opS7aY.png)

### 3) Configuring Teams
Select **Agents -> Teams** and click **Add New Team** to categorize employees by teams such as Online Banking or IT Support.


![3](https://github.com/user-attachments/assets/9420fbae-df62-4a71-a6cd-4def5728fdf3)



### 4) Ticket Permission
Navigate to **Settings -> User Settings** in the Admin Panel and **uncheck** the option "Require registration and login to create tickets." Click **Save Changes**.
This allows **unregistered users** to be able to create tickets.


### 5) Configuring Agents
In the Admin Panel, go to **Agents -> Add New Agent**. Create agents, assigning appropriate roles, access, and team memberships. I've created **Jane and John Doe**

![Capture2](https://github.com/user-attachments/assets/8e34b8c9-b8d7-4d30-a38b-06c58a417a44)


### 6) Adding New Users
Switch to the **Agent Panel** and go to **Users -> Add User** to create user accounts for clients or employees. **I've added Karen as our user.**

![Capture](https://github.com/user-attachments/assets/f32b6e1d-7b26-4e54-8738-6ac06ff9a1ef)



### 7) Configuring SLA's (Service Level Agreements)
In the Admin Panel, go to **Manage -> SLA** and click **Add New SLA Plan**. Define SLA levels:
- **Sev-A:** Grace Period: 1 hour, Schedule: 24/7
- **Sev-B:** Grace Period: 4 hours, Schedule: 24/7
- **Sev-C:** Grace Period: 8 hours, Schedule: Business Hours

![Capture9](https://github.com/user-attachments/assets/90cd5d21-2959-48a4-bb69-431c21cc8695)


### 8) Creating Help Topics
Go to **Manage -> Help Topics** and click **Add New Help Topic**. Define help topics to organize incoming tickets.
I created **Equipment Request, Other, Business Critical Outage, Password Reset, and Personal Computer Issues!**

![Capture10](https://github.com/user-attachments/assets/da9211a2-9a97-47c3-8659-d94a18c60ded)

****This concludes our osTicket Post-Installation Process! Congratulations, and I hope this guide helped!****

## Key Takeaways and Skills Developed

### **Technical Skills:**
- **System Administration:** Learned how to configure system roles, departments, and teams to streamline IT operations.
- **User Management:** Gained experience adding and managing users, a key responsibility in IT helpdesk environments.
- **Service Level Agreements (SLA):** Developed an understanding of setting up and applying SLA policies for ticket prioritization.
- **Helpdesk Ticketing Workflow:** Practiced configuring help topics and permissions, ensuring smooth ticket management.

### **Problem-Solving Skills:**
- **Issue Prioritization:** Understanding ticket management policies helps with effectively troubleshooting and resolving IT issues.
- **Team Collaboration:** Learned how to assign agents and create specialized teams for improved service response.

### **Professional Skills:**
- **Customer Service Orientation:** Setting user roles and ticket permissions highlights how IT professionals can improve customer interactions.
- **Documentation and Reporting:** Familiarity with detailed system configuration fosters better system documentation and reporting practices.



