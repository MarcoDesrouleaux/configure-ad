<p align="center">
<img src="https://i.imgur.com/pU5A58S.png" alt="Microsoft Active Directory Logo"/>
</p>

<h1>On-premises Active Directory Deployed in the Cloud (Azure)</h1>
This tutorial outlines the implementation of on-premises Active Directory within Azure Virtual Machines.<br />

## Prerequisites
- Active Microsoft Azure account
- Familiarity with Active Directory and Azure
- PowerShell installed

## Environments and Technologies Used
- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Active Directory Domain Services
- PowerShell

## Operating Systems Used
- Windows Server 2022
- Windows 10 (21H2)

## Step 1: Setting Up Azure Virtual Machines
1. Log in to your Azure portal.
2. Navigate to 'Create a resource' > 'Compute' > 'Virtual Machine.'
3. Configure the VM settings and ensure they meet the requirements for an Active Directory deployment.
4. Click 'Create' to deploy the VM.
<table>
<tr>
<td>
<img src="https://i.imgur.com/oixcf9e.png" alt="Image 1 Description" width="100%"/>
</td>
<td>
<img src="https://i.imgur.com/oixcf9e.png" alt="Image 1 Description" width="100%"/>
</td>
</tr>
</table>
<table>
<tr>
<td>
<img src="https://i.imgur.com/oixcf9e.png" alt="Image 1 Description" width="100%"/>
</td>
<td>
<img src="https://i.imgur.com/oixcf9e.png" alt="Image 1 Description" width="100%"/>
</td>
</tr>
</table>

## Step 2: Install Active Directory Domain Services
1. Connect to your Azure VM via Remote Desktop.
2. Install Active Directory Domain Services (AD DS) using PowerShell or Server Manager.
3. Run post-installation configuration.
<table>
<tr>
<td>
<img src="https://i.imgur.com/oixcf9e.png" alt="Image 1 Description" width="100%"/>
</td>
<td>
<img src="https://i.imgur.com/oixcf9e.png" alt="Image 1 Description" width="100%"/>
</td>
</tr>
</table>
<table>
<tr>
<td>
<img src="https://i.imgur.com/oixcf9e.png" alt="Image 1 Description" width="100%"/>
</td>
<td>
<img src="https://i.imgur.com/oixcf9e.png" alt="Image 1 Description" width="100%"/>
</td>
</tr>
</table>

## Step 3: Configure Active Directory

### 3.1 Create Users and Groups
1. Open Active Directory Administrative Center.
2. Navigate to the user and groups OU.
3. Create users and groups as needed.
<table>
<tr>
<td>
<img src="https://i.imgur.com/oixcf9e.png" alt="Image 1 Description" width="100%"/>
</td>
<td>
<img src="https://i.imgur.com/oixcf9e.png" alt="Image 1 Description" width="100%"/>
</td>
</tr>
</table>
<table>
<tr>
<td>
<img src="https://i.imgur.com/oixcf9e.png" alt="Image 1 Description" width="100%"/>
</td>
<td>
<img src="https://i.imgur.com/oixcf9e.png" alt="Image 1 Description" width="100%"/>
</td>
</tr>
</table>

### 3.2 Set Group Policies
1. Open Group Policy Management.
2. Create and link GPOs as necessary for your organization.
<table>
<tr>
<td>
<img src="https://i.imgur.com/oixcf9e.png" alt="Image 1 Description" width="100%"/>
</td>
<td>
<img src="https://i.imgur.com/oixcf9e.png" alt="Image 1 Description" width="100%"/>
</td>
</tr>
</table>
<table>
<tr>
<td>
<img src="https://i.imgur.com/oixcf9e.png" alt="Image 1 Description" width="100%"/>
</td>
<td>
<img src="https://i.imgur.com/oixcf9e.png" alt="Image 1 Description" width="100%"/>
</td>
</tr>
</table>
   
## Step 4: Test the Deployment
1. On a separate Azure VM, join the domain.
2. Test logging in with the user accounts you created.
3. Verify that Group Policies are applied as expected.
<table>
<tr>
<td>
<img src="https://i.imgur.com/oixcf9e.png" alt="Image 1 Description" width="100%"/>
</td>
<td>
<img src="https://i.imgur.com/oixcf9e.png" alt="Image 1 Description" width="100%"/>
</td>
</tr>
</table>
<table>
<tr>
<td>
<img src="https://i.imgur.com/oixcf9e.png" alt="Image 1 Description" width="100%"/>
</td>
<td>
<img src="https://i.imgur.com/oixcf9e.png" alt="Image 1 Description" width="100%"/>
</td>
</tr>
</table>

## Conclusion
Congratulations! You've successfully deployed an on-premises Active Directory environment in Azure. This allows for centralized identity and access management within your cloud resources.

<img src="https://i.imgur.com/oixcf9e.png" alt="Image 1 Description" width="100%"/>
