# osTicket Installation and Configuration in Azure

## Overview
This project involves setting up and configuring osTicket, an open-source support ticket system, on a Windows 10 Virtual Machine hosted in Microsoft Azure. This detailed guide covers the creation of the virtual environment, installation of necessary software components like IIS, PHP, and MySQL, and the deployment and configuration of osTicket for operational use.

## Environments and Technologies Used
- **Microsoft Azure**: Azure Virtual Machines, Virtual Networks
- **Internet Information Services (IIS)**
- **PHP and MySQL**
- **osTicket**: Open-source support ticket system
- **Operating Systems Used**:
  - Windows 10 VM

## High-Level Deployment and Configuration Steps
1. **VM Setup in Azure**:
   - Create a VM and configure it for web hosting.
2. **Software Installation**:
   - Install and configure IIS, PHP, MySQL, and necessary extensions.
3. **osTicket Installation**:
   - Deploy and configure osTicket within the IIS environment.
4. **Post-Installation Configuration and Testing**:
   - Finalize osTicket setup and perform functional tests.

## Detailed Deployment and Configuration Steps

### Step 1: VM Setup in Azure
- **Create Resource Group and Virtual Network**:
  - Start by creating a new resource group in Azure. Subsequently, set up a virtual network and a subnet to support the VMs.

- **Create Windows 10 Virtual Machine**:
  - Deploy a Windows 10 VM within the newly created resource group and virtual network, ensuring it has 2-4 Virtual CPUs and adequate memory.
  - Here is the new resource group and virtual network settings:
    ![image](https://github.com/00chazz/osticket-config/assets/63687898/0daba157-8d3e-4515-9694-6d09c6de9d90)

    
<br />

### Step 2: Software Installation
- **Install and Configure IIS**:
  - Install Internet Information Services (IIS) along with CGI and common HTTP features to support osTicket.
  - Install PHP Manager for IIS and configure PHP settings. Install MySQL and set up the initial osTicket database.
  - ISS set up with necessary extensions insalled:
    ![image](https://github.com/00chazz/osticket-config/assets/63687898/7a8fc58b-40f0-4fc0-96f1-77c0ec68b397)

    
<br />


### Step 3: osTicket Installation
- **Deploy osTicket**:
  - Download the osTicket installation files and unzip them to the designated directory within your IIS web root.
  - osTicket files on the IIS server, with PHP working and configured:
    ![image](https://github.com/00chazz/osticket-config/assets/63687898/fddecc40-abc3-41f2-95bc-e02246ad2b4a)

<br />

- **Web Configuration**:
  - Access the osTicket web installer via the browser using the VM’s public IP address. Proceed with the web-based installation, linking it to the MySQL database.
  - The completion screen after osTicket is successfully installed on the server:
    ![image](https://github.com/00chazz/osticket-config/assets/63687898/185f8fc6-de6a-45c7-8099-cd5ed96dffa2)
    ![image](https://github.com/00chazz/osticket-config/assets/63687898/022df31d-ff0f-42bd-a2cd-560f02661956)


    
<br />

### Step 4: Post-Installation Configuration and Testing
- **Configure osTicket System Settings**:
  - Set up roles, departments, teams, and SLAs via the osTicket admin panel to tailor the help desk to your organizational needs.
  - Roles and SLAs set up through the admin panel:
    ![image](https://github.com/00chazz/osticket-config/assets/63687898/ab51de12-2295-4dce-9626-3c559a281eca)
    ![image](https://github.com/00chazz/osticket-config/assets/63687898/2ca0ad69-7e85-45a8-bd71-ad5b8209de18)


    
<br />

- **Functionality Testing**:
  - Create, assign, and resolve tickets to ensure the system is functioning correctly.
  - A ticket being processed in osTicket:
    ![image](https://github.com/00chazz/osticket-config/assets/63687898/2e2ba097-e09a-48f2-a115-fb75717228df)

    
<br />

## Conclusion
Setting up osTicket on Azure demonstrates an effective integration of a ticket management system in a cloud environment, offering scalable customer support solutions.

## Connect with Me:
- **LinkedIn:** [Chazz Conino](https://www.linkedin.com/in/chazz-c-382a75122/)
