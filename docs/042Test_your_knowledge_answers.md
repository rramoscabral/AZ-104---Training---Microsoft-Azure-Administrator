---
layout: default
title: 'Test your knowledge - Answers'
parent: 'Exam certification'
nav_order: 2
has_children: false
---

# Test your knowledge - Answers

{: .no_toc }

<br/>

<a id="top" />


---


<a id="top" />

<br/>




# Test your knowledge - Answers


Topics

- [Manage Azure resources](#manageazureresources)
- [Manage access control](#manageaccesscontrol)
- [Automate deployment of resources by using Azure Resource Manager (ARM) templates or Bicep files](#armbicep)
- [Manage Azure identities and governance](#manageazureidentitiesgovernance)
- [Manage Network](#managenetwork)
- [Manage Storage](#managestorage)
- [Create and configure virtual machines](#createconfvm)
- [Create and configure Azure App Service](#appservice)
- [Manage Backup](#managebackup)
- [Kubernetes](#kubernetes)


<br>

---

<a id="manageazureresources" />

<br>



## Manage Azure resources

**Question 1:**

What are roles and how to use them?

**Answer:**

Role-Based Access Control (or RBAC) is the way you can configure access permissions to a resource (or group of resources) by an identity. It is a topic that is not complex but very important because it is the basis of the secure access configurations to our resources.



<br>

---

[**Return to top**](#top)

---

<a id="manageaccesscontrol" />

<br>

## Manage access control

**Question 1**

You have an Azure subscription that contains multiple users and administrators.
You are creating a new custom role by using the following JSON.

```json
{   
  "Name": "Custom Role",   
  "Id": null,   
  "IsCustom": true,   
  "Description": "Custom Role description",   
  "Actions": [
    "Microsoft.Compute/*/read",
    "Microsoft.Compute/snapshots/write",
    "Microsoft.Compute/snapshots/read",
    "Microsoft.Support/*"
  ],
  "NotActions": [   
          "Microsoft.Compute/snapshots/delete"   
  ],
  "AssignableScopes": [
    "/subscriptions/00000000-0000-0000-0000-000000000000",
    "/subscriptions/11111111-1111-1111-1111-111111111111"
  ] 
} 
```

Which three actions can be performed by a user that is assigned the custom role? Each correct answer presents a complete solution.

Select all answers that apply.
1. :heavy_check_mark: Call Microsoft Support.
1. Create and delete a snapshot.
1. :heavy_check_mark: Create and read a snapshot.
1. Create virtual machines.
1. :heavy_check_mark: Read all virtual machine settings.


**Answer:**

The role can read all compute resources, call Microsoft support roles, and allow the creation and reading of a snapshot.

Source:
- [Azure custom roles - Azure RBAC | Microsoft Learn](https://learn.microsoft.com/azure/role-based-access-control/custom-roles)
- [Configure role-based access control - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/configure-role-based-access-control/)

<br>


---

[**Return to top**](#top)

---

<a id="armbicep" />

<br>

## Automate deployment of resources by using Azure Resource Manager (ARM) templates or Bicep files


**Question 1:**

If there are many ways and tools to do this, which one do I use? Bicep, ARM Templates or some third party tool like Terraform?
 
**Answer:**

Here is a decision tree to assist you with the decision. Things to keep in mind include:
What is our strategy - single, or multi-cloud vendor?Are we already invested in a platform?Weigh up the effort of rewriting existing deployments with a new platform - especially if you are considering changing from ARM to BicepKeep in mind, consistency is there key here so try to stick to a single platform





<br>

---

[**Return to top**](#top)

---

<a id="manageazureidentitiesgovernance" />

<br>

## Manage Azure identities and governance 


**Question 1**

If there are many ways and tools to do this, which one do I use? Bicep, ARM Templates or some third party tool like Terraform?
 
**Answer:**

Here is a decision tree to assist you with the decision. Things to keep in mind include:
  - What is our strategy - single, or multi-cloud vendor?
  - Are we already invested in a platform?
  - Weigh up the effort of rewriting existing deployments with a new platform - especially if you are considering changing from ARM to Bicep.
  - Keep in mind, consistency is there key here so try to stick to a single platform.

<br>

**Question 2**

Explain what you mean by:
  - Understanding Azure Active Directory
  - Key Features of Azure AD
  - The Benefits of Azure AD
  - Azure AD the competitive edge


**Answer:**

**Understanding Azure Active Directory**

Azure AD is not just a regular directory service but a comprehensive cloud-based solution, facilitating seamless access to applications across organizational boundaries. It serves the dual purpose of Identity and Access Management (IAM) and Mobile Device Management (MDM), proving a versatile IT tool.

Using Azure AD, organizations can securely manage access to their networks, apps, and data based on the user's role and location. Employees can conveniently access services via single sign-on (SSO) without managing multiple usernames and passwords, making it an asset in an increasingly remote workforce scenario.

**Key Features of Azure AD**

| Feature | Description |
|  --- | --- |
| Identity and Access Management | Azure AD delivers rich, enterprise-level identity management capabilities, including single sign-on, password, and user-group management. One key benefit of Azure AD is its integration with the Microsoft ecosystem, as illustrated by a large-scale retailer who simplified IT management by integrating Azure AD with Microsoft Intune and Office 365, resulting in centralized control and enhanced security. |
| User and Group Management | Azure AD allows centralized management of user identities. Creating, modifying, and deleting users and groups in a centralized database provides an efficient approach to handling network objects. This feature lets administrators control who has access to what information, ensuring only authorized individuals have access to sensitive data. |
| Single Sign-On (SSO): | SSO functionality simplifies the user experience by allowing users to log in once and gain access to multiple applications. This feature significantly reduces the number of login prompts for end-users. |
| Multi-Factor Authentication (MFA) | Azure AD Multi-Factor Authentication is a pillar of its security strategy, adding an extra layer of protection to user sign-ins and transactions. By requiring two or more authentication methods, Azure AD MFA significantly reduces the risk of unauthorized access. A multinational corporation reportedly reduced its security incidents by 98% after adopting Azure AD MFA.| 
| Conditional Access | With Azure AD's conditional access feature, organizations can define and enforce policies based on user location, device, and application sensitivity, ensuring secure access. A healthcare provider implemented conditional access to secure patient data, significantly dropping data breaches and improving compliance with healthcare regulations.|
| On-premises Directory Synchronization | Azure AD can synchronize with your on-premises Active Directory, ensuring consistency between local and cloud user identities.|
| Self-Service Password Reset | This feature allows cloud users to change their passwords without IT intervention, reducing administrative overhead. |
| Device Management | Azure AD extends its reach to device management, allowing organizations to control resource access based on the device's compliance status. Microsoft Intune, integrated with Azure AD, can manage devices and ensure they meet the organization's security standards before accessing resources |


**The Benefits of Azure AD**

| Benefit | Description |
| --- | --- |
| Increased Security and Compliance | Azure AD offers robust security features like MFA, conditional access, and identity protection, which help guard against 99.9 percent of cybersecurity attacks. |
| Centralized Management | Azure AD allows for centralized management of user identities, enhancing operational efficiency. |
 |Simplified Access | With SSO and self-service features, users can easily access the necessary resources, improving productivity. |
| High Availability | Azure AD is hosted on a global network of data centers, ensuring high availability and performance. |
| Enhanced Collaboration | Azure AD enables secure collaboration within and outside the organization. Users can easily access Microsoft 365, the Azure portal, and thousands of other SaaS applications. |
| Access from Anywhere | As a cloud-based service, Azure AD allows users to access resources from anywhere, which is especially valuable for remote work scenarios. |

**Azure AD the competitive edge**

While solutions such as Okta and Google Cloud Identity also offer cloud-based IAM services, Azure AD's seamless integration with Microsoft's ecosystem gives it a unique edge. With its exceptional scalability, strong security measures like Multi-Factor Authentication and Conditional Access, and device management capabilities, Azure AD is an excellent choice for enterprises of varying sizes.

In conclusion, Azure AD is an effective solution in an increasingly cloud-centric world, offering organizations a secure and efficient system to manage identities, access, and devices. As businesses grapple with the challenges of a growing remote workforce, Azure AD's robust and multi-layered approach toward security can prove to be a game-changer.


<br>

**Question 3** 

What is the difference between a tenant an Azure Active Directory\Entra?


**Answer:**

Tenant is essential the top level in the hierarchy that gives you the onmicrosoft.com. The tenant is associated to your Azure AD directory\Entra ID. Can the tenant have multiple tenants. Yes. This is a multiple-tenant organization. Azure Active Directory\Entra ID is your directory database. What contains your directory and domain(s). It is what you use to manage your users\groups and security of all of that. 


Source: 
- [What is Azure Active Directory? - Microsoft Entra | Microsoft Learn](https://learn.microsoft.com/en-us/azure/active-directory/fundamentals/active-directory-whatis)
- [What is a multi-tenant organization in Azure Active Directory? - Microsoft Entra | Microsoft Learn](https://learn.microsoft.com/en-us/azure/active-directory/multi-tenant-organizations/overview#what-is-a-multi-tenant-organization) 


<br>


**Question 4**

You plan to create 100 new users by using the Bulk create users operation in the Azure portal.
You need to create a CSV file that contains the user information.
Which attributes should you specify in the CSV file for each user?

Select only one answer.
1. displayName, givenName, surname, and department
1. :heavy_check_mark: displayName, userPrincipalName, passwordProfile, and accountEnabled
1. givenName, surname, usageLocation, and department
1. userPrincipalName, givenName, usageLocation, and country


**answer**

When you use the Bulk create users operation, you must specify four things: 
  - the display name, the UPN, the initial password, and whether the account is enabled or disabled. 
All other fields are optional.

Source:
- [Bulk create users in the Azure Active Directory portal - Microsoft Entra | Microsoft Learn](https://learn.microsoft.com/azure/active-directory/enterprise-users/users-bulk-add)
- [Configure user and group accounts - Training | Microsoft Learn](https://learn.microsoft.com/training/modules/configure-user-group-accounts/)


<br>

---

[**Return to top**](#top)

---


<a id="managenetwork" />

<br>

## Manage Network

**Question 1:**

Your company has VMs in Azure that are in the VNet1 azure virtual network,Employees work from their home office and need access to the VMs in VNet1.
You need to make sure they have secure access. 
What should you do?
 
  1.  Configure a Site-to-Site VPN.
  1.  Configure a Windows Server 2012 on-premises with DirectAccess
  1.  :heavy_check_mark: Configure Point-Site-VPN for each worker
  1.  Configure a Virtual WAN.
  1.  Configure a Express Route VPN.


**Answer:**

- Correct answer: Configure Point-Site-VPN for each worker
- Source: https://learn.microsoft.com/en-us/azure/vpn-gateway/point-to-site-about


<br>

---

[**Return to top**](#top)

---

<a id="managestorage" />

<br>

## Manage Storage

**Question 1**

What is Azure Storage Account Object Replication?

**Answer**

Object Replication is an asynchronous, inter-region data replication feature in Azure Blob Storage. It empowers you to set up custom, fine-grained data replication beyond the scope of the default storage account replication options.

In simpler terms, Azure's Object Replication allows you to specify exactly which blobs (or objects) to replicate, instead of replicating the entire storage account. This gives you greater control and flexibility over what data you want to replicate and where you want it replicated to.

<br>

---

[**Return to top**](#top)


---

<a id="createconfvm" />

<br>

## Create and configure virtual machines

**Question 1**

When would I use Availability Sets vs Virtual Machine Scale Sets?


**Answer:**

With Availability Sets you are making your workloads highly available due to a planned maintenance, unplanned maintenance and\or unexpected downtime. You do this by deploying more than one workload in a set and they get deployed across more than fault and update domains. Therefore if one domain is not available you have other workloads in another domain that can pick up the slack. 
As for VMSS it is all about performance. Meeting planned or unplanned performance spikes in your workloads. With VMSS you can scale your VMs vertically or horizontally. Vertical is changing the sku of the VM and is manual. Whereas horizontal is adding VMs when your performance requires it. This can be automatic based on rules that are monitoring the avg VMs memory or CPU. 
AVSet = Redundancy
VMSS = Performance 



<br>


**Question 2**

If we have 2 VMSS autoscaling profiles one for "scaling using a metric" and another one for scaling using a schedule, so if there is a conflict which policy would take effect
 
**Answer:** 

If you have two auto scale profiles for a VMSS, one based on a metric and another based on a schedule,Each time the auto scale service runs, the profiles are evaluated in the following order:
1. Fixed date profiles
1. Recurring profiles
1. Default profile
 

If a profile's date and time settings match the current time, autoscale will apply that profile's rules and capacity limits. Only the first applicable profile is used.
The example below shows an auto scale setting with a default profile and recurring profile.
 
 
In the above example, on Monday after 3 AM, the recurring profile will cease to be used. If the instance count is less than 3, auto scale scales to the new minimum of three. Auto scale continues to use this profile and scales based on CPU% until Monday at 8 PM. At all other times scaling will be done according to the default profile, based on the number of requests. After 8 PM on Monday, auto scale switches to the default profile. If for example, the number of instances at the time is 12, auto scale scales in to 10, which the maximum allowed for the default profile.
 
Source:
- [Autoscale with multiple profiles - Azure Monitor | Microsoft Learn](https://learn.microsoft.com/en-us/azure/azure-monitor/autoscale/autoscale-multiprofile?tabs=templates)
- [Troubleshoot autoscale with Virtual Machine Scale Sets - Azure Virtual Machine Scale Sets | Microsoft Learn](https://learn.microsoft.com/en-us/azure/virtual-machine-scale-sets/virtual-machine-scale-sets-troubleshoot)

<br>

---

[**Return to top**](#top)


---

<a id="appservice" />

<br>

## Create and configure Azure App Service

**Question 1**

If I want to make use of slots purely to get a zero downtime deployment, what do I have to do and what configuration options offer this.

**Answer:**

There is an auto-swap feature, but it is only available for Windows hosts and not Linux.
You can see the option under the Configuration > General section of the slot you want to swap from.

Source: [Set up staging environments - Azure App Service | Microsoft Learn](https://learn.microsoft.com/en-us/azure/app-service/deploy-staging-slots?tabs=portal#configure-auto-swap)



<br>

---

[**Return to top**](#top)


---

<a id="managebackup" />

<br>

## Manage Backup


**Question 1:** 

Can you backup your virtual machines to the cloud from your office?


**Answer:**

Yes you can. You use the Azure Recovery Services Vault. You can install the MARS (Microsoft Azure Recovery Services) agent on any Windows platform and backup to the cloud. Or if you have non-windows or many servers you want to back up you can use MABS (Microsoft Azure Backup Server).

Source: https://learn.microsoft.com/en-us/azure/backup/install-mars-agent


<br>

---

[**Return to top**](#top)

---

<a id="kubernetes" />

<br>


##  Kubernetes


**Question 1:**

When regulating access to an Azure Kubernetes service (AKS), are there other options as opposed to only using Kubernetes built-in role based access control (RBAC)

**Answer:**

AKS has three options for managing access to the API server and services:
  - Option 1, the afore mentioned option from the question is built-in RBAC for Kubernetes where access (roles and role bindings) are managed internally within the AKS cluster. This is very similar to SQL server authentication where roles are defined in the server without any knowledge about AAD.
  - Option 2 makes use of Azure AD  (AAD) from a security principal perspective, but still leverages the built in AKS RBAC in the cluster. This makes use of a combination of AAD and built-in RBAC from the cluster.
  - Option 3 only makes use of AAD from a security principal perspective, but also makes use of Azure RBAC for managing access to the cluster and does not leverage the built-in RBAC of Kubernetes for this.


Source: [Concepts - Access and identity in Azure Kubernetes Services (AKS) - Azure Kubernetes Service | Microsoft Learn](https://learn.microsoft.com/en-us/azure/aks/concepts-identity)

<br>

---

<br>


