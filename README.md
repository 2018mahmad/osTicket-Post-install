<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
<p>The following video tutorial provides a detailed overview of the post-installation configuration process for the open-source help desk ticketing system, osTicket. In this tutorial, we will take the system from its initial setup to a fully operational help desk system, ready for handling real-world support tickets.</p>

<h2>Video Demonstration</h2>

- ### [YouTube: osTicket Tutorial (Part 2/3) Configuration](enterlinkhere)

## 📌 Project Overview

This project demonstrates the post-installation configuration and optimization of an osTicket Help Desk Ticketing System to transform a basic installation into a fully operational, enterprise-style IT support platform. The focus is on configuring roles, departments, teams, agents, users, SLAs, and help topics to support real-world Help Desk and IT Service Management (ITSM) workflows.

This project aligns with responsibilities commonly found in **IT Support**, **Help Desk Technician**, and **System Administrator** roles.

## 🎯 Business Problem

A ticketing system is only effective when it is properly structured. Without defined roles, departments, priorities, and SLAs, support requests become disorganized and difficult to manage.

This project addresses that problem by implementing a logical configuration that improves:

- Ticket routing and ownership  
- Prioritization of critical incidents  
- Accountability and escalation  
- Consistent user experience

## ⚙️ Key Configuration Areas

- Role-based access control (RBAC)  
- Department and team structure  
- Agent and user management  
- Service Level Agreements (SLAs)  
- Help topic categorization

## 🧰 Technologies Used

- Windows 10 Pro (21H2)  
- Microsoft Azure Virtual Machines  
- osTicket  
- Internet Information Services (IIS)  
- PHP  
- MySQL  
- Remote Desktop Protocol (RDP)

## 🏗️ Environment Overview

- Windows 10 virtual machine hosting IIS  
- osTicket deployed as a web application  
- MySQL backend database  
- Admin and Agent panels used for configuration

## 🔁 Configuration Workflow

1. Configure roles and permissions  
2. Create departments and teams  
3. Add agents and users  
4. Define SLAs and priorities  
5. Create help topics for ticket categorization

## 🔧 Configuration Highlights

### Roles & Permissions
- Created administrative and support roles  
- Implemented role-based access control  

### Departments & Teams
- System Administrators  
- Level I Support  
- Level II Support  

### Agents & Users
- Added support agents for ticket handling  
- Added end users for ticket submission  

### Service Level Agreements (SLAs)
- Sev-A: 1 hour, 24/7 (critical outages)  
- Sev-B: 4 hours, 24/7 (high-priority issues)  
- Sev-C: 8 hours, business hours (low priority)  

## 📚 What I Learned

- Implementing role-based access control  
- Designing department and team structures  
- Applying ITSM best practices  
- Configuring SLAs and ticket priorities  
- Managing users and agents  
- Hardening a ticketing system for production use  

## 🚧 Challenges & Solutions

**Issue:** Tickets were not being routed efficiently.  
**Solution:** Implemented departments, help topics, and SLAs to ensure proper categorization and prioritization.

