# osTicket Installation and Configuration in Azure

## Overview
This project documents my setup and configuration of an osTicket help desk environment on a Windows 10 virtual machine in Microsoft Azure. I installed the required web and database components, deployed osTicket, configured core support settings, and tested ticket workflows from creation to resolution.

This project helped me build hands-on familiarity with help desk software, ticket lifecycle management, and the kind of support processes used in real IT environments.

## What This Project Shows
- Basic help desk and ticketing workflow knowledge
- Experience installing and configuring support software
- Familiarity with ticket intake, triage, assignment, and resolution
- Understanding of roles, departments, SLAs, and support structure
- Exposure to Windows-based web hosting and application setup
- Practice documenting and testing a support system end to end

## Environments and Technologies Used
- **Microsoft Azure**: Virtual Machines, Virtual Networks
- **Windows 10 VM**
- **Internet Information Services (IIS)**
- **PHP**
- **MySQL**
- **osTicket**

## High-Level Deployment and Configuration Steps
1. Create and configure a Windows 10 virtual machine in Azure
2. Install IIS, PHP, MySQL, and required extensions
3. Deploy and configure osTicket
4. Set up support roles, departments, teams, and SLAs
5. Test ticket creation, assignment, and resolution workflows

---

## Detailed Deployment and Configuration Steps

### Step 1: Azure VM Setup
I created a new Azure resource group, virtual network, and subnet, then deployed a Windows 10 virtual machine to host the osTicket environment.

This provided the foundation for:
- hosting the application
- testing browser access
- simulating a support platform in a cloud environment

![image](https://github.com/00chazz/osticket-config/assets/63687898/0daba157-8d3e-4515-9694-6d09c6de9d90)

<br />

### Step 2: Install Required Software
I installed and configured the supporting components needed for osTicket, including:
- IIS
- CGI and common HTTP features
- PHP and PHP Manager
- MySQL

This step gave me hands-on exposure to preparing a Windows system for hosting a web-based support platform.

![image](https://github.com/00chazz/osticket-config/assets/63687898/7a8fc58b-40f0-4fc0-96f1-77c0ec68b397)

<br />

### Step 3: Deploy osTicket
I downloaded and deployed the osTicket files into the IIS web root, then confirmed that PHP and the supporting environment were working correctly before launching the web installer.

![image](https://github.com/00chazz/osticket-config/assets/63687898/fddecc40-abc3-41f2-95bc-e02246ad2b4a)

<br />

### Step 4: Configure the Application
Using the browser-based installer, I connected osTicket to the MySQL database and completed the initial setup process.

This step reinforced:
- application deployment basics
- web-based configuration
- database-backed support system setup

![image](https://github.com/00chazz/osticket-config/assets/63687898/185f8fc6-de6a-45c7-8099-cd5ed96dffa2)
![image](https://github.com/00chazz/osticket-config/assets/63687898/022df31d-ff0f-42bd-a2cd-560f02661956)

<br />

### Step 5: Configure Support Structure
After installation, I configured the osTicket environment by setting up:
- roles
- departments
- teams
- SLAs

This helped me understand how structured support environments organize requests, permissions, escalation paths, and service expectations.

![image](https://github.com/00chazz/osticket-config/assets/63687898/ab51de12-2295-4dce-9626-3c559a281eca)
![image](https://github.com/00chazz/osticket-config/assets/63687898/2ca0ad69-7e85-45a8-bd71-ad5b8209de18)

<br />

### Step 6: Test Ticket Workflow
I created, assigned, and resolved tickets within the system to validate that the platform was functioning properly.

This gave me hands-on practice with:
- ticket intake
- ticket assignment
- issue tracking
- resolution workflow

![image](https://github.com/00chazz/osticket-config/assets/63687898/2e2ba097-e09a-48f2-a115-fb75717228df)

<br />

## Outcome
By completing this project, I gained practical exposure to the setup and operation of a help desk platform in a cloud-hosted environment. It strengthened my understanding of:

- support ticket workflows
- help desk structure and escalation concepts
- Windows-based application hosting
- documentation and process-driven support

Overall, this project gave me a stronger foundation in the type of tools and workflows commonly used in IT support roles.
