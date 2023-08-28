<a id="top" />

<br/>


[**Back to main**](./README.md)


# Test your knowledge - Questions


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


<br>

---

[**Return to top**](#top) |  [**Back to main**](./README.md)

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
1. Call Microsoft Support.
1. Create and delete a snapshot.
1. Create and read a snapshot.
1. Create virtual machines.
1. Read all virtual machine settings.


<br>


---

[**Return to top**](#top) |  [**Back to main**](./README.md)

---

<a id="armbicep" />

<br>

## Automate deployment of resources by using Azure Resource Manager (ARM) templates or Bicep files


**Question 1:**

If there are many ways and tools to do this, which one do I use? Bicep, ARM Templates or some third party tool like Terraform?
 

<br>

---

[**Return to top**](#top) |  [**Back to main**](./README.md)

---

<a id="manageazureidentitiesgovernance" />

<br>

## Manage Azure identities and governance 


**Question 1**

If there are many ways and tools to do this, which one do I use? Bicep, ARM Templates or some third party tool like Terraform?
 


<br>

**Question 2**

Explain what you mean by:
  - Understanding Azure Active Directory
  - Key Features of Azure AD
  - The Benefits of Azure AD
  - Azure AD the competitive edge



<br>

**Question 3** 

What is the difference between a tenant an Azure Active Directory\Entra?



<br>


**Question 4**

You plan to create 100 new users by using the Bulk create users operation in the Azure portal.
You need to create a CSV file that contains the user information.
Which attributes should you specify in the CSV file for each user?

Select only one answer.
1. displayName, givenName, surname, and department
1. displayName, userPrincipalName, passwordProfile, and accountEnabled
1. givenName, surname, usageLocation, and department
1. userPrincipalName, givenName, usageLocation, and country

<br>

---

[**Return to top**](#top) |  [**Back to main**](./README.md)

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
  1.  Configure Point-Site-VPN for each worker
  1.  Configure a Virtual WAN.
  1.  Configure a Express Route VPN.


<br>

---

[**Return to top**](#top) |  [**Back to main**](./README.md)

---

<a id="managestorage" />

<br>

## Manage Storage

**Question 1**

What is Azure Storage Account Object Replication?



<br>

---

[**Return to top**](#top) |  [**Back to main**](./README.md)


---

<a id="createconfvm" />

<br>

## Create and configure virtual machines

**Question 1**

When would I use Availability Sets vs Virtual Machine Scale Sets?



<br>


**Question 2**

If we have 2 VMSS autoscaling profiles one for "scaling using a metric" and another one for scaling using a schedule, so if there is a conflict which policy would take effect
 

<br>

---

[**Return to top**](#top) |  [**Back to main**](./README.md)


---

<a id="appservice" />

<br>

## Create and configure Azure App Service

**Question 1**

If I want to make use of slots purely to get a zero downtime deployment, what do I have to do and what configuration options offer this.


<br>

---

[**Return to top**](#top) |  [**Back to main**](./README.md)


---

<a id="managebackup" />

<br>

## Manage Backup


**Question 1:** 

Can you backup your virtual machines to the cloud from your office?


<br>

---

[**Return to top**](#top) |  [**Back to main**](./README.md)

---

<a id="kubernetes" />

<br>


##  Kubernetes


**Question 1:**

When regulating access to an Azure Kubernetes service (AKS), are there other options as opposed to only using Kubernetes built-in role based access control (RBAC)


<br>

---

<br>

[**Back to main**](./README.md)
