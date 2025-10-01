![image](https://github.com/user-attachments/assets/c9c71901-6014-4e83-aec1-38d7fb023d58)


<h1>Microsoft Azure - Creating Resource Groups and Virtual Machines</h1>
This tutorial outlines the steps to create and configure resource groups and virtual machines in Microsoft Azure.<br />

<h2>Video Demonstration</h2>

### [YouTube: How To Create Resource Groups and Virtual Machines in Azure](https://youtu.be/lBxtKG255aQ)



<h2>Step By Step</h2>

<img width="1500" height="1438" alt="azure_rg_vm_steps1-2_fixed_title" src="https://github.com/user-attachments/assets/24cd991d-f792-4926-90ad-aa70a1d7a7ab" />





<h2>Environments and Technologies Used</h2>

- **Microsoft Azure** (Resource Groups/Virtual Machines)
- **Remote Desktop Protocol (RDP)**
- **Windows Admin Center**

<h2>Operating Systems Used</h2>

- **Windows 10** (21H2)

---

<h2>Part 1: Create a Virtual Machine in Azure</h2>

**1. Create a Resource Group:**
   - Navigate to the Azure portal.
   - Select **"Resource groups"** and click **"Add"**.
   - Enter the following:
     - **Name**: *Example: AzureResourceGroup*
     - **Region**: *Select your preferred region*.
   - Click **"Review + create"**, then **"Create"**.

**2. Create a Windows 10 Virtual Machine (VM):**
   - Go to the Azure portal home page.
   - Select **"Create a resource"** and then choose **"Virtual Machine"**.
   - Fill in the following settings:
     - **Name**: *Example: AzureVM-Windows10*
     - **Region**: *Your preferred region*.
     - **Image**: Windows 10 Pro or Enterprise.
     - **Size**: *Select a VM size (e.g., 2-4 vCPUs for testing)*.
     - **Username**: *Example: labuser*.
     - **Password**: *Strong password, e.g., AzurePassword123!*
   - In the **Networking** section, allow it to create a new Virtual Network (VNet).
   - Click **"Review + create"**, then **"Create"**.
