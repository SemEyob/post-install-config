


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
Login to your Admin account using this link: `http://localhost/osTicket/scp/login.php`. Switch to the **Admin Panel** and navigate to **Agents -> Roles** to create and manage roles.

![Configuring Roles](https://i.imgur.com/4YWjpPw.png)

### 2) Configuring Departments
Go to **Agents -> Departments** and click **Add New Department**. Fill in the relevant department information and click **Create Dept**.

![Adding Departments](https://i.imgur.com/DUSkjV2.png)
![Department Details](https://i.imgur.com/4opS7aY.png)

### 3) Configuring Teams
Select **Agents -> Teams** and click **Add New Team** to categorize employees by teams such as Online Banking or IT Support.


![Creating Teams](https://i.imgur.com/beJJui0.png)
![Team Details](https://i.imgur.com/sC7KfIB.png)

### 4) Ticket Permission
Navigate to **Settings -> User Settings** in the Admin Panel and **uncheck** the option "Require registration and login to create tickets." Click **Save Changes**.

![Ticket Permissions](https://i.imgur.com/Aiy83sH.png)

### 5) Configuring Agents
In the Admin Panel, go to **Agents -> Add New Agent**. Create agents, assigning appropriate roles, access, and team memberships.

![Adding Agents](https://i.imgur.com/eTNky7o.png)
![Agent Details](https://i.imgur.com/djXrSwE.png)

### 6) Adding New Users
Switch to the **Agent Panel** and go to **Users -> Add User** to create user accounts for clients or employees.

![Adding Users](https://i.imgur.com/aYjjVS4.png)

### 7) Configuring SLA's (Service Level Agreements)
In the Admin Panel, go to **Manage -> SLA** and click **Add New SLA Plan**. Define SLA levels:
- **Sev-A:** Grace Period: 1 hour, Schedule: 24/7
- **Sev-B:** Grace Period: 4 hours, Schedule: 24/7
- **Sev-C:** Grace Period: 8 hours, Schedule: Business Hours

![Adding SLA](https://i.imgur.com/B2CFz7s.png)
![SLA Details](https://i.imgur.com/h7c9392.png)

### 8) Creating Help Topics
Go to **Manage -> Help Topics** and click **Add New Help Topic**. Define help topics to organize incoming tickets.

![Creating Help Topics](https://i.imgur.com/xBiVw0n.png)
![Help Topic Details](https://i.imgur.com/wsDdFdc.png)

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

This concludes our osTicket Post-Installation Process! Congratulations, and I hope this guide helped!

In this project, I configured osTicket by managing user roles, departments, and ticket settings. I set up roles to group permissions, defined departments for ticket visibility, and created teams by combining agents from different departments. I required user registration before ticket creation, added agents and users, and set up SLAs for different severity levels. Additionally, I created help topics to categorize tickets. This hands-on experience helped me learn to manage user roles, workflows, and settings in a ticketing system to improve help desk efficiency.
