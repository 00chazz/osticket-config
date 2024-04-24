# osTicket Installation and Configuration in Azure

## Overview
This project involved setting up a Windows VM, installing and configuring IIS, PHP, MySQL, and deploying osTicket. Skills displayed include VM setup, web server configuration, database management, application deployement.


## Environments and Technologies Used
- **Microsoft Azure**: Azure Virtual Machines (VMs)
- **Internet Information Services (IIS)**
- **PHP and MySQL**
- **osTicket**: Open-source support ticket system
- **Operating Systems Used**:
  - Windows 10

## High-Level Deployment and Configuration Steps
1. **VM Setup in Azure**:
   - Create and configure a Windows 10 Virtual Machine in Azure.
2. **Software Installation**:
   - Install and configure IIS, PHP, MySQL, and other prerequisites on the VM.
3. **osTicket Installation**:
   - Install and configure osTicket within the IIS environment on the Azure VM.
4. **Post-Installation Configuration and Testing**:
   - Configure osTicket settings and perform functionality testing.

## Detailed Deployment and Configuration Steps


### Step 1: VM Setup in Azure
- **Create Resource Group and VM**:
  - In the Azure portal, create a new resource group and then set up a Windows 10 VM with necessary specifications (2-4 CPUs, 8 GB RAM).
  - **Screenshot**: Capture the Azure portal screen showing the VM specifications and resource group details.

### Step 2: Software Installation
- **Install IIS with Required Features**:
  - Install IIS via the Server Manager, adding features like CGI and Application Development Features necessary for running PHP applications.
  - **Screenshot**: Display the IIS dashboard with the installed features highlighted.

- **Install and Configure PHP**:
  - Download and configure PHP Manager for IIS and set up PHP to work within the IIS environment.
  - **Screenshot**: Show the PHP version and configuration settings in the IIS PHP Manager.

- **Install MySQL**:
  - Install MySQL Server and perform initial setup, including configuring a root password and setting up the osTicket database.
  - **Screenshot**: Capture the MySQL installation summary and initial setup screens.

### Step 3: osTicket Installation
- **Deploy osTicket Files**:
  - Download osTicket from the provided link, extract the files, and place them in the IIS root directory configured for web access.
  - **Screenshot**: Show the osTicket files in their directory on the server.

- **Configure osTicket**:
  - Run the osTicket installer through a web browser by accessing the VM's public IP, configure system settings, and connect it to the MySQL database.
  - **Screenshot**: Capture the final screen of the osTicket setup wizard indicating successful installation.

### Step 4: Testing
- **Functionality Testing**:
  - Test creating a ticket, assigning a ticket, and responding to a ticket within the osTicket system to ensure all functions are operational.
  - **Screenshot**: Display a test ticket fully created and visible in the osTicket dashboard.

## Conclusion
Setting up osTicket on Azure demonstrates an effective integration of a ticket management system in a cloud environment, offering scalable customer support solutions.

## Connect with Me
- **LinkedIn:** [Chazz C](https://www.linkedin.com/in/chazz-c-382a75122/)
