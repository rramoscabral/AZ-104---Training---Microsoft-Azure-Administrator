<a id="top" />

<br/>

[**Back to Exam certification**](./exam.md) | [**Back to main**](./README.md)

<br/>

---

AZ-104 Microsoft Azure Administrator Sample Questions 

Last updated: 2022/01/26 


Microsoft is exploring the possibility of providing sample questions as an exam preparation resource, and we would like your feedback. 
 
User Guide 

These sample questions are intended to provide an overview of the style, wording, and difficulty of the questions that you are likely to experience on this exam. These questions are **not** the same as what you will see on the exam nor is this document illustrative of the length of the exam or its complexity (e.g., you may see additional question types, multiple case studies, and possibly labs). These questions are **examples** only to provide insight into what to expect on the exam and help you determine if additional preparation is required. 

In the first section, you will find the questions without answers so that you can test your knowledge. 

In the second section, the answer, a rationale, and a URL that will link you to additional information is provided immediately below each question. 

Contents 

---
## Questions  

### Question # 1  (Multiple Choice) 
Your company has a Microsoft 365 tenant and an Azure Active Directory (Azure AD) tenant named contoso.com. The company uses several Azure Files shares. Each share is assigned to a different department at the company. The department attribute in Azure AD is populated for all users. 

You need to ensure that the users can access the departmental file shares. 

Which two types of groups should you use? Each correct presents a complete solution. 

1. a security group that uses the dynamic membership type 
1. a Microsoft 365 group that uses the dynamic membership type 
1. a distribution group that uses the dynamic membership type 
1. a security group that uses the assigned membership type 
1. a Microsoft 365 group that uses the assigned membership type 

<br/>

[Return to top](#top) | [Back to main](./README.md)

<br/>

### Question # 2  (Multiple Choice) 
You have an Azure Active Directory (Azure AD) tenant named contoso.com. 

You need to ensure that a user named User1 can review all the settings of the tenant. User1 must be prevented from changing any settings. 

Which role should you assign to User1? 

1. Directory reader 
1. Security reader 
1. Reports reader 
1. Global reader 

<br/>

[Return to top](#top) | [Back to main](./README.md)

<br/>


### Question # 3  (Multiple Choice) 
You have a production Azure Active Directory (Azure AD) tenant named contoso.com. 

You deploy a development Azure Active Directory (AD) tenant, and then you create several custom administrative roles in the development tenant. 

You need to copy the roles to the production tenant. What should you do first? 

1. From the development tenant, export the custom roles to JSON. 
1. From the production tenant, create a new custom role. 
1. From the development tenant, perform a backup. 
1. From the production tenant, create an administrative unit. 


<br/>

[Return to top](#top) | [Back to main](./README.md)

<br/>


### Question # 4  (Multiple Choice – 3) 
You have an Azure subscription that contains several hundred virtual machines. You need to identify which virtual machines are underutilized. 

What should you use? 

1. Azure Advisor 
1. Azure Monitor 
1. Azure policies 

<br/>

[Return to top](#top) | [Back to main](./README.md)

<br/>




### Question # 5  (Multiple Choice) 
Your company has 10 different departments.  

You have an Azure subscription that contains several hundred virtual machines. The users of each department use only their department’s virtual machines. 

You plan to apply resource tags for each department to the virtual machines. Which two solutions should you use? Each correct presents a complete solution. 

1. PowerShell 
1. Azure Resource Manager (ARM) templates 
1. app registrations 
1. Azure Advisor 

<br/>

[Return to top](#top) | [Back to main](./README.md)

<br/>


### Question # 6  (Multiple Choice) 

You have an Azure subscription that contains the storage accounts shown in the following table. 



|**Name** |**Kind** |**Performance** |**Replication** |
| - | - | - | - |
|storage1 |StorageV2 (general purpose v2) |Standard |Zone-redundant storage (ZRS) |
|storage2 |BlobStorage |Standard |Locally-redundant storage (LRS) |
|storage3 |FileStorage |Premium |Zone-redundant storage (ZRS) |
|storage4 |Storage (general purpose v1) |Premium |Locally-redundant storage (LRS) |

You need to identify which storage accounts can be switched to geo-redundant storage (GRS). Which storage accounts should you identify? 

1. storage1 only 
1. storage2 only 
1. storage3 only 
1. storage4 only 
1. storage1 and storage4 only 
1. storage2 and storage3 only 

<br/>

[Return to top](#top) | [Back to main](./README.md)

<br/>


### Question # 7  (Multiple Choice) 
You have an Azure subscription that contains several Azure runbooks. The runbooks run nightly and generate reports. The runbooks are configured to store authentication credentials as variables. 

You need to replace the authentication solution with a more secure solution. What should you use? 

1. Azure Active Directory (Azure AD) Identity Protection 
1. Azure Key Vault 
1. an access policy 
1. an administrative unit 

<br/>

[Return to top](#top) | [Back to main](./README.md)

<br/>



### Question # 8  (Multiple Choice) 

You have a resource group named RG1 that contains several unused resources. 

You need to use the Azure CLI to remove RG1 and all its resources, without requiring a confirmation. 

Which command should you use? 

1. az group delete --name rg1 --no-wait --yes 
1. az group deployment delete --name rg1 --no-wait 
1. az group update --name rg1 --remove 
1. az group wait –deleted –resource-group rg1 

<br/>

[Return to top](#top) | [Back to main](./README.md)

<br/>


### Question # 9  (Multiple Choice) 
You have an Azure virtual machine named VM1. 

You need to create five additional virtual machines that have the same configurations as VM1. The solution must ensure that VM1 remains available. 

From the Azure portal, you open the blade for VM1. What should you do next? 

1. Select **Capture**. 
1. Select **Availability and scaling**. 
1. Select **Redeploy + reapply**. 
1. Select **Export template**. 

<br/>

[Return to top](#top) | [Back to main](./README.md)

<br/>


### Question # 10 (Multiple Choice) 
You have an Azure subscription that contains an Azure App Service web app named webapp1. Webapp1 uses a domain name of webapp1.azurewebsites.net. 

You need to add a custom domain named www.contoso.com to webapp1. 

You verify the domain ownership. 

Which DNS record should you use next? 

1. SRV 
1. CNAME 
1. TXT 
1. PTR 


<br/>

[Return to top](#top) | [Back to main](./README.md)

<br/>


### Question # 11 (Multiple Choice) 

You have an Azure subscription that contains a virtual machine named VM1. 

VM1 requires volume encryption for its operating system and data disks. 

You create an Azure key vault named vault1. 

You need to configure vault1 to support Azure Disk Encryption for volume encryption. 

Which setting should you modify for vault1? 

1. Keys 
1. Secrets 
1. Access policies 
1. Security 

<br/>

[Return to top](#top) | [Back to main](./README.md)

<br/>


### Question # 12 (Multiple Choice) 
You have an Azure subscription that contains the resources shown in the following table. 



|**Name** |**Description** |
| - | - |
|VM1 |Azure virtual machine |
|Blob1 |Azure Blob Storage |
|Disk1 |Azure Disk |
|Share1 |Azure Files storage |
|Database1 |Azure Database for PostgreSQL servers |

Which two resources can you back up to a Recovery Services vault? Each correct presents part of the solution. 

1. VM1 
1. Blob1 
1. Disk1 
1. Share1 
1. Database1 


<br/>

[Return to top](#top) | [Back to main](./README.md)

<br/>

### Case Study


**Overview** 

Contoso, Ltd. is a consulting company. The company has a main office in Vancouver and branch offices in Seattle and New York. 

**Existing Environment** 

**Azure Environment** 

Contoso has two Azure subscriptions named ContosoSub1 and ContosoSub2. ContosoSub1 has the resource group shown in the following table. 


|**Name** |**Lock name** |**Lock type** |**Location** |
| - | - | - | - |
|ResourceGroup1 |Lock1 |Read Only |West US |

ResourceGroup1 contains the resources shown in the following table. 



|**Name** |**Type** |**Tag** |**IP address space** |**Location** |
| - | - | - | - | - |
|Disk1 |Managed disk |RG:1 |*Not applicable* |West US |
|Vnet1 |Virtual network |RG:1 |10\.40.0.0/20 |West US |

ContosoSub2 has the resource group shown in the following table. 



|**Name** |**Lock name** |**Lock type** |**Region** |
| - | - | - | - |
|ResourceGroup2 |Lock 2 |Delete |East US |

ResourceGroup2 contains the resources shown in the following table. 



|**Name** |**Type** |**Tag** |**IP address space** |**Location** |
| - | - | - | - | - |
|Disk2 |Managed disk |RG:2 |*Not applicable*  |East US |
|Vnet2 |Virtual network |RG:2 |10\.40.0.0/22 |East US |

Contoso has an Azure Active Directory (Azure AD) tenant named contoso.com that contains the user accounts shown in the following table. 



|**Name** |**Role** |**Office** |
| - | - | - |
|Admin1 |Domain name administrator |Vancouver |
|Admin2 |User administrator |Vancouver |
|Admin3 |Helpdesk administrator |Vancouver |
|User1 |*Not applicable* |New York |
|User2 |*Not applicable* |Seattle |

**Azure Storage Environment** 

ContosoSub1 contains the storage accounts shown in the following table. 



|**Name** |**Kind** |
| - | - |
|ContosoStorage1 |StorageV2 (general purpose v2) |
|ContosoStorage2 |FileStorage |
|ContosoStorage3 |BlockBlobStorage |
|ContosoStorage4 |Storage (general purpose v1) |

Contoso has the Recovery Service vaults shown in the following table. 



|**Name** |**Backup contains** |**Storage replication type** |
| - | - | - |
|Rsv1 |Azure File shares |Geo-redundant storage (GRS) |
|Rsv2 |Virtual machines |Geo-redundant storage (GRS) |
|Rsv3 |No items |Geo-redundant storage (GRS) |

**Problem Statement** 

- Administrators share the ContosoStorage2 access key with external users. 
- Replication costs for backups are over budget. 

**Requirements** 

**Planned Changes** 

Contoso plans to implement the following changes: 

- Configure backups to use locally-redundant storage (LRS) replication whenever possible. 
- Hire 125 new employees, each of whom will require an account created in the tenant. 
- Delegate User1 to manage all the user and group accounts in the New York office. 
- Delegate User2 to manage all the user and group accounts in the Seattle office. 
- Deploy a new Azure virtual machine named DevVM1 that will run Windows 10. 
- Create peering between Vnet1 and Vnet2. 
- Move Disk1 to ResourceGroup2. 

**Technical Requirements** 

Contoso must meet the following technical requirements: 

- For supported storage accounts, data not accessed for 60 days must be moved automatically to cool storage. Data not accessed for 120 days must be moved automatically to archive storage. 
- DevVM1 must be accessible from the Azure portal over TLS and provide seamless RDP/SSH connectivity. 
- Delegated administrative permissions must be scoped to specific locations. 
- Administrative effort and costs must be minimized whenever possible. 
- The principle of least privilege must be used. 

**Security Requirements** 

Contoso must meet the following security requirements: 

- User access to storage account data must be granted for a specified start and expiration date and time. 
- DevVM1 must be protected from port scanning from outside the virtual network. 
- Storage account access keys must not be shared directly with users. 


<br/>

[Return to top](#top) | [Back to main](./README.md)

<br/>


### Question # 13 (Multiple Choice)

**Answer the following question based on the information presented in the case study.**

Which administrator can implement the planned changes for the new employees?
1. Admin1 only
1. Admin2 only
1. Admin3 only
1. Admin1 and Admin2 only
1. Admin1 and Admin3 only


<br/>

[Return to top](#top) | [Back to main](./README.md)

<br/>


###  Question # 14 (Multiple Choice)

**Answer the following question based on the information presented in the case study.**


You need to implement the planned changes for User1 and User2.
What should you do first?
1. Create two new resource groups.
1. Create two new management groups.
1. Create two new named locations.
1. Create two new administrative units.

<br/>

[Return to top](#top) | [Back to main](./README.md)

<br/>


###  Question # 15 (Multiple Choice)

**Answer the following question based on the information presented in the case study.**

You need to implement the planned changes for Disk1.
What should you do first?
1. Add ContosoSub1 and ContosoSub2 to a new management group.
1. Remove Lock1 from ResourceGroup1.
1. Modify the RG:1 tag.
1. Remove Lock2 from ResourceGroup2.



<br/>

[Return to top](#top) | [Back to main](./README.md)

<br/>




### Question # 16 (Multiple Choice) 

**Answer the following question based on the information presented in the case study.** 

1. Admin1 only 
1. Admin2 only 
1. Admin3 only 
1. Admin1 and Admin2 only 
1. Admin1 and Admin3 only 

What should you do first? 

1. Create two new resource groups. 
1. Create two new management groups. 
1. Create two new named locations. 
1. Create two new administrative units. 


<br/>

[Return to top](#top) | [Back to main](./README.md)

<br/>



### Question # 15 (Multiple Choice) 

**Answer the following question based on the information presented in the case study.** You need to implement the planned changes for Disk1. 

What should you do first? 

1. Add ContosoSub1 and ContosoSub2 to a new management group. 
1. Remove Lock1 from ResourceGroup1. 
1. Modify the RG:1 tag. 
1. Remove Lock2 from ResourceGroup2. 

Which storage accounts meet the technical requirements? 

1. ContosoStorage1 and ContosoStorage4 only 
1. ContosoStorage2 and ContosoStorage3 only 
1. ContosoStorage1 and ContosoStorage3 only 
1. ContosoStorage2 and ContosoStorage4 only 


<br/>

[Return to top](#top) | [Back to main](./README.md)

<br/>



### Question # 17 (Multiple Choice) 

**Answer the following question based on the information presented in the case study.** 

You need to address the issue that relates to ContosoStorage2. The solution must meet the security requirements. 

What should you do? 

1. Set a rotation reminder for the access keys. 
1. Configure a lifecycle management rule. 
1. Create a new access review. 
1. Generate a shared access signature (SAS). 


<br/>

[Return to top](#top) | [Back to main](./README.md)

<br/>


### Question # 18 (Multiple Choice) 

**Answer the following question based on the information presented in the case study.** 

You need to implement the planned changes for Vnet1 and Vnet2. What should you do first? 

1. Move Vnet1 to the East US Azure region. 
1. Move Vnet2 to the ContosoSub1 subscription. 
1. Modify the tag for Vnet2 
1. Modify the address space for Vnet1.


<br/>

[Return to top](#top) | [Back to main](./README.md)

<br/>



### Question # 19 (Multiple Choice) 
**Answer the following question based on the information presented in the case study.** Before you deploy DevVM1, you need to consider the technical and security requirements. What should you do to ensure that access to DevVM1 is secure? 

1. Install the Azure Virtual Desktop client on all the devices that will connect to DevVM1. 
1. Deploy the Azure Bastion service. 
1. Configure Remote Desktop Gateway on all the devices that will connect to DevVM1. 
1. Configure the Azure Network Watcher service. 


<br/>

[Return to top](#top) | [Back to main](./README.md)

<br/>




### Question # 20 (Multiple Choice) 
**Answer the following question based on the information presented in the case study.** 

You need to resolve the issue that relates to the replication costs for backups. 

Which Recovery Services vault can be configured to use locally-redundant storage (LRS) replication? 

1. Rsv1 only 
1. Rsv2 only 
1. Rsv3 only 
1. Rsv1 and Rsv2 only 
1. Rsv1, Rsv2, and Rsv3 


---


# Questions and Answers 

### Question # 1  (Multiple Choice) 
Your company has a Microsoft 365 tenant and an Azure Active Directory (Azure AD) tenant named contoso.com. The company uses several Azure Files shares. Each share is assigned to a different department at the company. The department attribute in Azure AD is populated for all users. 

You need to ensure that the users can access the departmental file shares. 

Which two types of groups should you use? Each correct presents a complete solution. 

1. a security group that uses the dynamic membership type 
1. a Microsoft 365 group that uses the dynamic membership type 
1. a distribution group that uses the dynamic membership type 
1. a security group that uses the assigned membership type 
1. a Microsoft 365 group that uses the assigned membership type 



<table><tr><th colspan="1" valign="top"><b>Answer:</b>  </th><th colspan="1" valign="top">A AND B </th></tr>
<tr><td colspan="1" valign="top"><b>Objective:</b>  </td><td colspan="1" valign="top">1\.1 Manage Azure Active Directory (Azure AD) objects </td></tr>
<tr><td colspan="1" valign="top"><b>Rationale:</b> </td><td colspan="1" valign="top">Groups that use dynamic membership rules reduce the overhead of access management by providing attribute-based membership and access to resources.  Based on membership rules the membership, and resulting access, can be granted and removed automatically. </td></tr>
<tr><td colspan="1" rowspan="2" valign="top"><b>URL:</b> </td><td colspan="1" valign="top">[Rules for dynamically populated groups membership - Azure AD | Microsoft Docs](https://docs.microsoft.com/en-us/azure/active-directory/enterprise-users/groups-dynamic-membership)</td></tr>
<tr><td colspan="1"></td></tr>
</table>


<br/>

[Return to top](#top) | [Back to main](./README.md)

<br/>



### Question # 2  (Multiple Choice) 
You have an Azure Active Directory (Azure AD) tenant named contoso.com. 

You need to ensure that a user named User1 can review all the settings of the tenant. User1 must be prevented from changing any settings. 

Which role should you assign to User1? 

1. Directory reader 
1. Security reader 
1. Reports reader 
1. Global reader 



<table><tr><th colspan="1" valign="top"><b>Answer:</b>  </th><th colspan="1" valign="top">D </th></tr>
<tr><td colspan="1" valign="top"><b>Objective:</b>  </td><td colspan="1" valign="top">1\.2 Manage role-based access control (RBAC) </td></tr>
<tr><td colspan="1" valign="top"><b>Rationale:</b> </td><td colspan="1" valign="top">A user that is assigned the Global reader role is prevented from making any modifications. The role is a read-only version of Global Administrator that allows the user to read settings and administrative information across all services but can't take management actions. </td></tr>
<tr><td colspan="1" rowspan="2" valign="top"><b>URL:</b> </td><td colspan="1" valign="top">[https://docs.microsoft.com/en-us/azure/active-directory/roles/permissions-](https://docs.microsoft.com/en-us/azure/active-directory/roles/permissions-reference#global-reader)</td></tr>
<tr><td colspan="1" valign="top">[reference#global-reader](https://docs.microsoft.com/en-us/azure/active-directory/roles/permissions-reference#global-reader)</td></tr>
</table>


<br/>

[Return to top](#top) | [Back to main](./README.md)

<br/>



### Question # 3  (Multiple Choice) 

You have a production Azure Active Directory (Azure AD) tenant named contoso.com. 

You deploy a development Azure Active Directory (AD) tenant, and then you create several custom administrative roles in the development tenant. 

You need to copy the roles to the production tenant. What should you do first? 

1. From the development tenant, export the custom roles to JSON. 
1. From the production tenant, create a new custom role. 
1. From the development tenant, perform a backup. 
1. From the production tenant, create an administrative unit. 



<table><tr><th colspan="1" valign="top"><b>Answer:</b>  </th><th colspan="1" valign="top">A </th></tr>
<tr><td colspan="1" valign="top"><b>Objective:</b>  </td><td colspan="1" valign="top">1\.2 Manage role-based access control (RBAC) </td></tr>
<tr><td colspan="1" valign="top"><b>Rationale:</b> </td><td colspan="1" valign="top">Creating Custom roles in Azure can be complex due to thousands of permissions so custom roles can be exported as JSON and then imported into a new custom role. The first step is to export the role to a JSON format. A JSON file can then be imported into another tenant; containing all of the details in the custom role. </td></tr>
<tr><td colspan="1" rowspan="2" valign="top"><b>URL:</b> </td><td colspan="1" valign="top">[https://docs.microsoft.com/en-us/azure/role-based-access-control/custom-roles](https://docs.microsoft.com/en-us/azure/role-based-access-control/custom-roles)</td></tr>
<tr><td colspan="1"></td></tr>
</table>



<br/>

[Return to top](#top) | [Back to main](./README.md)

<br/>



### Question # 4  (Multiple Choice – 3) 
You have an Azure subscription that contains several hundred virtual machines. You need to identify which virtual machines are underutilized. 

What should you use? 

1. Azure Advisor 
1. Azure Monitor 
1. Azure policies 



<table><tr><th colspan="1" valign="top"><b>Answer:</b>  </th><th colspan="1" valign="top">A </th></tr>
<tr><td colspan="1" valign="top"><b>Objective:</b>  </td><td colspan="1" valign="top">5\. Monitor and back up Azure resources </td></tr>
<tr><td colspan="1" valign="top"><b>Rationale:</b> </td><td colspan="1" valign="top">Azure Advisor can be used to quickly optimize the Azure Deployments.  It provides various dashboard to support Cost, Reliability, Security and Performance. </td></tr>
<tr><td colspan="1" rowspan="2" valign="top"><b>URL:</b> </td><td colspan="1" valign="top">[https://azure.microsoft.com/en-us/services/advisor/](https://azure.microsoft.com/en-us/services/advisor/)</td></tr>
<tr><td colspan="1"></td></tr>
</table>



<br/>

[Return to top](#top) | [Back to main](./README.md)

<br/>



### Question # 7  (Multiple Choice) 

Your company has 10 different departments.  

You have an Azure subscription that contains several hundred virtual machines. The users of each department use only their department’s virtual machines. 

You plan to apply resource tags for each department to the virtual machines. Which two solutions should you use? Each correct presents a complete solution. 

1. PowerShell 
1. Azure Resource Manager (ARM) templates 
1. app registrations 
1. Azure Advisor 



<table><tr><th colspan="1" valign="top"><b>Answer:</b>  </th><th colspan="1" valign="top">A AND B </th></tr>
<tr><td colspan="1" valign="top"><b>Objective:</b>  </td><td colspan="1" valign="top">1\.3 Manage subscriptions and governance. </td></tr>
<tr><td colspan="1" valign="top"><b>Rationale:</b> </td><td colspan="1" valign="top">Assigning Tags to Virtual machines will allow you create reports and dashboards for Alerting, budget and performance management. Tags can be applied by using PowerShell, Azure CLI, and ARM templates. </td></tr>
<tr><td colspan="1" rowspan="2" valign="top"><b>URL:</b> </td><td colspan="1" valign="top">[https://docs.microsoft.com/en-us/azure/cloud-adoption-framework/decision-](https://docs.microsoft.com/en-us/azure/cloud-adoption-framework/decision-guides/resource-tagging/)</td></tr>
<tr><td colspan="1" valign="top">[guides/resource-tagging/](https://docs.microsoft.com/en-us/azure/cloud-adoption-framework/decision-guides/resource-tagging/) </td></tr>
</table>

You have an Azure subscription that contains the storage accounts shown in the following table. 



|**Name** |**Kind** |**Performance** |**Replication** |
| - | - | - | - |
|storage1 |StorageV2 (general purpose v2) |Standard |Zone-redundant storage (ZRS) |
|storage2 |BlobStorage |Standard |Locally-redundant storage (LRS) |
|storage3 |FileStorage |Premium |Zone-redundant storage (ZRS) |
|storage4 |Storage (general purpose v1) |Premium |Locally-redundant storage (LRS) |

You need to identify which storage accounts can be switched to geo-redundant storage (GRS). Which storage accounts should you identify? 

1. storage1 only 
1. storage2 only 
1. storage3 only 
1. storage4 only 
1. storage1 and storage4 only 
1. storage2 and storage3 only 



<table><tr><th colspan="1" valign="top"><b>Answer:</b>  </th><th colspan="1" valign="top">B </th></tr>
<tr><td colspan="1" valign="top"><b>Objective:</b>  </td><td colspan="1" valign="top">2\.2 Manage storage </td></tr>
<tr><td colspan="1" valign="top"><b>Rationale:</b> </td><td colspan="1" valign="top">Geo-redundant storage (GRS) copies your data synchronously three times within a single physical location in the primary region using LRS. It then copies your data asynchronously to a single physical location in a secondary region that is hundreds of miles away from the primary region. Storage accounts configured with the Premium performance setting only support LRS. Any storage account already configured with ZRS cannot be changed or directly switched to another replication setting.  In this scenario, the only storage account that is not set to LRS or Premium performance is storage2, which can be switched to use Geo-redundant storage. </td></tr>
<tr><td colspan="1" rowspan="2" valign="top"><b>URL:</b> </td><td colspan="1" valign="top">[https://docs.microsoft.com/en-us/azure/storage/common/storage-redundancy](https://docs.microsoft.com/en-us/azure/storage/common/storage-redundancy) </td></tr>
<tr><td colspan="1"></td></tr>
</table>
You have an Azure subscription that contains several Azure runbooks. The runbooks run nightly and generate reports. The runbooks are configured to store authentication credentials as variables. 

You need to replace the authentication solution with a more secure solution. What should you use? 

1. Azure Active Directory (Azure AD) Identity Protection 
1. Azure Key Vault 
1. an access policy 
1. an administrative unit 



<table><tr><th colspan="1" valign="top"><b>Answer:</b>  </th><th colspan="1" valign="top">B </th></tr>
<tr><td colspan="1" valign="top"><b>Objective:</b>  </td><td colspan="1" valign="top">5\.2 Implement backup and recovery </td></tr>
<tr><td colspan="1" valign="top"><b>Rationale:</b> </td><td colspan="1" valign="top">A runbook requires appropriate credentials to access any resource, whether for Azure or third-party systems. These credentials can be stored in Key Vault and then referenced to access resources. </td></tr>
<tr><td colspan="1" rowspan="2" valign="top"><b>URL:</b> </td><td colspan="1" valign="top">[https://docs.microsoft.com/en-us/azure/automation/automation-runbook-](https://docs.microsoft.com/en-us/azure/automation/automation-runbook-execution)</td></tr>
<tr><td colspan="1" valign="top">[execution](https://docs.microsoft.com/en-us/azure/automation/automation-runbook-execution) </td></tr>
</table>



<br/>

[Return to top](#top) | [Back to main](./README.md)

<br/>



### Question # 8  (Multiple Choice) 
You have a resource group named RG1 that contains several unused resources. 

You need to use the Azure CLI to remove RG1 and all its resources, without requiring a confirmation. 

Which command should you use? 

1. az group delete --name rg1 --no-wait --yes 
1. az group deployment delete --name rg1 --no-wait 
1. az group update --name rg1 --remove 
1. az group wait –deleted –resource-group rg1 



<table><tr><th colspan="1" valign="top"><b>Answer:</b>  </th><th colspan="1" valign="top">A </th></tr>
<tr><td colspan="1" valign="top"><b>Objective:</b>  </td><td colspan="1" valign="top">1\.3 Manage subscriptions and governance </td></tr>
<tr><td colspan="1" valign="top"><b>Rationale:</b> </td><td colspan="1" valign="top">To remove a resource group using Azure CLI you would use the az group delete command. The –no-wait switch specifies to not wait for long-running operations before you can continue using the open command prompt for additional commands, and the –yes switch specifies no prompt for confirmation. </td></tr>
<tr><td colspan="1" rowspan="2" valign="top"><b>URL:</b> </td><td colspan="1" valign="top">[https://docs.microsoft.com/en-us/cli/azure/group?view=azure-cli-](https://docs.microsoft.com/en-us/cli/azure/group?view=azure-cli-latest#az_group_delete)</td></tr>
<tr><td colspan="1" valign="top">[latest#az_group_delete;](https://docs.microsoft.com/en-us/cli/azure/group?view=azure-cli-latest#az_group_delete)  </td></tr>
</table>


<br/>

[Return to top](#top) | [Back to main](./README.md)

<br/>



### Question # 9  (Multiple Choice) 

You have an Azure virtual machine named VM1. 

You need to create five additional virtual machines that have the same configurations as VM1. The solution must ensure that VM1 remains available. 

From the Azure portal, you open the blade for VM1. What should you do next? 

1. Select **Capture**. 
1. Select **Availability and scaling**. 
1. Select **Redeploy + reapply**. 
1. Select **Export template**. 



<table><tr><th colspan="1" valign="top"><b>Answer:</b>  </th><th colspan="1" valign="top">D </th></tr>
<tr><td colspan="1" valign="top"><b>Objective:</b>  </td><td colspan="1" valign="top">3\.1 Automate deployment of virtual machines (VMs) by using Azure Resource Manager templates </td></tr>
<tr><td colspan="1" valign="top"><b>Rationale:</b> </td><td colspan="1" valign="top"><p>If you need to create multiple Azure resources based upon an existing resource, you should export and use a JSON template. You can export a template from the resource itself, from a resource group, or from the deployment history. In this scenario, you would export the template from the VM1 blade. </p><p>You would only use Capture if you wanted to create an image of the existing VM. However, this will make the source VM unusable. There are also several preparation tasks to complete before capturing the VM image. You would not select Redeploy + reapply as these two options are used to address failed connections or VM states. Availability and scaling is used to set up and manage VM high availability, not for creating additional VMs based upon a set configuration setting. </p></td></tr>
<tr><td colspan="1" rowspan="3" valign="top"><b>URL:</b> </td><td colspan="1" valign="top">[https://docs.microsoft.com/en-us/azure/azure-resource-](https://docs.microsoft.com/en-us/azure/azure-resource-manager/templates/export-template-portal)</td></tr>
<tr><td colspan="1" valign="top">[manager/templates/export-template-portal](https://docs.microsoft.com/en-us/azure/azure-resource-manager/templates/export-template-portal)</td></tr>
<tr><td colspan="1"></td></tr>
</table>


<br/>

[Return to top](#top) | [Back to main](./README.md)

<br/>




### Question # 10 (Multiple Choice) 
You have an Azure subscription that contains an Azure App Service web app named webapp1. Webapp1 uses a domain name of webapp1.azurewebsites.net. 

You need to add a custom domain named www.contoso.com to webapp1. 

You verify the domain ownership. 

Which DNS record should you use next? 

1. SRV 
1. CNAME 
1. TXT 
1. PTR 



<table><tr><th colspan="1" valign="top"><b>Answer:</b>  </th><th colspan="1" valign="top">B  </th></tr>
<tr><td colspan="1" valign="top"><b>Objective:</b>  </td><td colspan="1" valign="top">3\.4 Create and configure Azure App Services  </td></tr>
<tr><td colspan="1" valign="top"><b>Rationale:</b> </td><td colspan="1" valign="top">When you add a custom domain to an App Service, you need to validate the domain to verify domain ownership. To verify domain ownership for contoso.com you will create a txt record that contains the Custom Domain Verification ID. The CNAME record is used to map www.contoso.com to webapp.azurewebsites.net. </td></tr>
<tr><td colspan="1" rowspan="2" valign="top"><b>URL:</b> </td></tr>
<tr><td colspan="1" valign="top"></td></tr>
</table>


<br/>

[Return to top](#top) | [Back to main](./README.md)

<br/>

### Question # 11 (Multiple Choice) 

You have an Azure subscription that contains a virtual machine named VM1. 

VM1 requires volume encryption for its operating system and data disks. 

You create an Azure key vault named vault1. 

You need to configure vault1 to support Azure Disk Encryption for volume encryption. 

Which setting should you modify for vault1? 

1. Keys 
1. Secrets 
1. Access policies 
1. Security 



<table><tr><th colspan="1" valign="top"><b>Answer:</b>  </th><th colspan="1" valign="top">C </th></tr>
<tr><td colspan="1" valign="top"><b>Objective:</b>  </td><td colspan="1" valign="top">3\.2 Configure VMs </td></tr>
<tr><td colspan="1" valign="top"><b>Rationale:</b> </td><td colspan="1" valign="top">To enable support for Azure Disk Encryption, you need to modify the Access policies for the key vault. This provides an option to enable access to Azure Disk Encryption for volume encryption. </td></tr>
<tr><td colspan="1" rowspan="2" valign="top"><b>URL:</b> </td><td colspan="1" valign="top">[https://docs.microsoft.com/en-us/azure/virtual-machines/windows/disk-](https://docs.microsoft.com/en-us/azure/virtual-machines/windows/disk-encryption-key-vault)</td></tr>
<tr><td colspan="1" valign="top">[encryption-key-vault](https://docs.microsoft.com/en-us/azure/virtual-machines/windows/disk-encryption-key-vault) </td></tr>
</table>


<br/>

[Return to top](#top) | [Back to main](./README.md)

<br/>



### Question # 12 (Multiple Choice) 

You have an Azure subscription that contains the resources shown in the following table. 



|**Name** |**Description** |
| - | - |
|VM1 |Azure virtual machine |
|Blob1 |Azure Blob Storage |
|Disk1 |Azure Disk |
|Share1 |Azure Files storage |
|Database1 |Azure Database for PostgreSQL servers |

Which two resources can you back up to a Recovery Services vault? Each correct presents part of the solution. 

1. VM1 
1. Blob1 
1. Disk1 
1. Share1 
1. Database1 



<table><tr><th colspan="1" valign="top"><b>Answer:</b>  </th><th colspan="1" valign="top">A AND D </th></tr>
<tr><td colspan="1" valign="top"><b>Objective:</b>  </td><td colspan="1" valign="top">5\.2 Implement backup and recovery </td></tr>
<tr><td colspan="1" valign="top"><b>Rationale:</b> </td><td colspan="1" valign="top">Recovery Services vault supports Azure Virtual Machines, SQL in Azure VM, Azure Files, SAP HANA in Azure VM, Azure Backup Server, Azure Backup Agent, and DPM. Backup vault supports Azure Database for PostgreSQL servers, Azure Blobs, and Azure disks. </td></tr>
<tr><td colspan="1" rowspan="2" valign="top"><b>URL:</b> </td></tr>
<tr><td colspan="1" valign="top"></td></tr>
</table>


<br/>

[Return to top](#top) | [Back to main](./README.md)

<br/>



### Case Study 

**Overview** 

Contoso, Ltd. is a consulting company. The company has a main office in Vancouver and branch offices in Seattle and New York. 

**Existing Environment** 

**Azure Environment** 

Contoso has two Azure subscriptions named ContosoSub1 and ContosoSub2. ContosoSub1 has the resource group shown in the following table. 



|**Name** |**Lock name** |**Lock type** |**Location** |
| - | - | - | - |
|ResourceGroup1 |Lock1 |Read Only |West US |

ResourceGroup1 contains the resources shown in the following table. 



|**Name** |**Type** |**Tag** |**IP address space** |**Location** |
| - | - | - | - | - |
|Disk1 |Managed disk |RG:1 |*Not applicable* |West US |
|Vnet1 |Virtual network |RG:1 |10\.40.0.0/20 |West US |

ContosoSub2 has the resource group shown in the following table. 



|**Name** |**Lock name** |**Lock type** |**Region** |
| - | - | - | - |
|ResourceGroup2 |Lock 2 |Delete |East US |

ResourceGroup2 contains the resources shown in the following table. 



|**Name** |**Type** |**Tag** |**IP address space** |**Location** |
| - | - | - | - | - |
|Disk2 |Managed disk |RG:2 |*Not applicable*  |East US |
|Vnet2 |Virtual network |RG:2 |10\.40.0.0/22 |East US |

Contoso has an Azure Active Directory (Azure AD) tenant named contoso.com that contains the user accounts shown in the following table. 



|**Name** |**Role** |**Office** |
| - | - | - |
|Admin1 |Domain name administrator |Vancouver |
|Admin2 |User administrator |Vancouver |
|Admin3 |Helpdesk administrator |Vancouver |
|User1 |*Not applicable* |New York |
|User2 |*Not applicable* |Seattle |


**Azure Storage Environment** 

ContosoSub1 contains the storage accounts shown in the following table. 



|**Name** |**Kind** |
| - | - |
|ContosoStorage1 |StorageV2 (general purpose v2) |
|ContosoStorage2 |FileStorage |
|ContosoStorage3 |BlockBlobStorage |
|ContosoStorage4 |Storage (general purpose v1) |

Contoso has the Recovery Service vaults shown in the following table. 



|**Name** |**Backup contains** |**Storage replication type** |
| - | - | - |
|Rsv1 |Azure File shares |Geo-redundant storage (GRS) |
|Rsv2 |Virtual machines |Geo-redundant storage (GRS) |
|Rsv3 |No items |Geo-redundant storage (GRS) |

**Problem Statement** 

- Administrators share the ContosoStorage2 access key with external users. 
- Replication costs for backups are over budget. 

**Requirements** 

**Planned Changes** 

Contoso plans to implement the following changes: 

- Configure backups to use locally-redundant storage (LRS) replication whenever possible. 
- Hire 125 new employees, each of whom will require an account created in the tenant. 
- Delegate User1 to manage all the user and group accounts in the New York office. 
- Delegate User2 to manage all the user and group accounts in the Seattle office. 
- Deploy a new Azure virtual machine named DevVM1 that will run Windows 10. 
- Create peering between Vnet1 and Vnet2. 
- Move Disk1 to ResourceGroup2. 

**Technical Requirements** 

Contoso must meet the following technical requirements: 

- For supported storage accounts, data not accessed for 60 days must be moved automatically to cool storage. Data not accessed for 120 days must be moved automatically to archive storage. 
- DevVM1 must be accessible from the Azure portal over TLS and provide seamless RDP/SSH connectivity. 

￿  Delegated administrative permissions must be scoped to specific locations. ￿  Administrative effort and costs must be minimized whenever possible. ￿  The principle of least privilege must be used. 

**Security Requirements** 

Contoso must meet the following security requirements: 

- User access to storage account data must be granted for a specified start and expiration date and time. 
- DevVM1 must be protected from port scanning from outside the virtual network. 
- Storage account access keys must not be shared directly with users. 


<br/>

[Return to top](#top) | [Back to main](./README.md)

<br/>


### Question # 13 (Multiple Choice) 

**Answer the following question based on the information presented in the case study.** 

A. Admin1 only 
B. Admin2 only 
C. Admin3 only 
D. Admin1 and Admin2 only 
E. Admin1 and Admin3 only 


<table><tr><th colspan="1" valign="top"><b>Answer:</b>  </th><th colspan="5" valign="top">B </th></tr>
<tr><td colspan="1" valign="top"><b>Objective:</b>  </td><td colspan="5" valign="top">Objective 1.1: Manage Azure Active Directory (Azure AD) objects </td></tr>
<tr><td colspan="1" rowspan="8" valign="top"><b>Rationale:</b> </td><td colspan="5" valign="top"><p>To bulk create users in the Azure AD administration portal, you must be signed in as a Global administrator or User administrator. Only Admin2 has the User administrator role to perform the task. </p><p>===================== <b>From the Case Study: Azure Environment:</b> </p></td></tr>
<tr><td colspan="2" valign="top"><b>Name</b> </td><td colspan="1" valign="top"><b>Administrative Role</b> </td><td colspan="1" valign="top"><b>Location</b> </td></tr>
<tr><td colspan="2" valign="top">Admin1 </td><td colspan="1" valign="top">Domain name administrator </td><td colspan="1" valign="top">Vancouver </td></tr>
<tr><td colspan="2" valign="top">Admin2 </td><td colspan="1" valign="top">User administrator </td><td colspan="1" valign="top">Vancouver </td></tr>
<tr><td colspan="2" valign="top">Admin3 </td><td colspan="1" valign="top">Helpdesk administrator </td><td colspan="1" valign="top">Vancouver </td></tr>
<tr><td colspan="2" valign="top">User1 </td><td colspan="1" valign="top">N/A </td><td colspan="1" valign="top">New York </td></tr>
<tr><td colspan="2" valign="top">User2 </td><td colspan="1" valign="top">N/A </td><td colspan="1" valign="top">Seattle </td></tr>
<tr><td colspan="1" valign="top"><p><b>Technical requirements:</b> </p><p>Minimize administrative effort and cost whenever possible. ==================== </p></td></tr>
<tr><td colspan="1" rowspan="2" valign="top"><b>URL:</b> </td><td colspan="5" valign="top">[https://docs.microsoft.com/en-us/azure/active-directory/enterprise-users/users-](https://docs.microsoft.com/en-us/azure/active-directory/enterprise-users/users-bulk-add)</td></tr>
<tr><td colspan="5" valign="top">[bulk-add](https://docs.microsoft.com/en-us/azure/active-directory/enterprise-users/users-bulk-add) </td></tr>
</table>


<br/>

[Return to top](#top) | [Back to main](./README.md)

<br/>


### Question # 14 (Multiple Choice) 

**Answer the following question based on the information presented in the case study.** 

You need to implement the planned changes for User1 and User2. What should you do first? 

A. Create two new resource groups. 
B. Create two new management groups. 
C. Create two new named locations. 
D. Create two new administrative units. 



<table><tr><th colspan="1" valign="top"><b>Answer:</b>  </th><th colspan="5" valign="top">D </th></tr>
<tr><td colspan="1" valign="top"><b>Objective:</b>  </td><td colspan="5" valign="top">Objective 1.1: Manage Azure Active Directory (Azure AD) objects </td></tr>
<tr><td colspan="1" rowspan="8" valign="top"><b>Rationale:</b> </td><td colspan="5" valign="top"><p>You use Administrative units to logically group Azure AD resources. You first create the Administrative units for each location. You can then assign User1 and User2 the User administrator role for each of their associated Administrative units and then add the users and groups that should be managed members. </p><p>===================== <b>From the Case Study: Azure Environment:</b> </p></td></tr>
<tr><td colspan="2" valign="top"><b>Name</b> </td><td colspan="1" valign="top"><b>Administrative Role</b> </td><td colspan="1" valign="top"><b>Location</b> </td></tr>
<tr><td colspan="2" valign="top">Admin1 </td><td colspan="1" valign="top">Domain name administrator </td><td colspan="1" valign="top">Vancouver </td></tr>
<tr><td colspan="2" valign="top">Admin2 </td><td colspan="1" valign="top">User administrator </td><td colspan="1" valign="top">Vancouver </td></tr>
<tr><td colspan="2" valign="top">Admin3 </td><td colspan="1" valign="top">Helpdesk administrator </td><td colspan="1" valign="top">Vancouver </td></tr>
<tr><td colspan="2" valign="top">User1 </td><td colspan="1" valign="top">N/A </td><td colspan="1" valign="top">New York </td></tr>
<tr><td colspan="2" valign="top">User2 </td><td colspan="1" valign="top">N/A </td><td colspan="1" valign="top">Seattle </td></tr>
<tr><td colspan="1" valign="top"><p><b>Planned Changes:</b> </p><p>Delegate User1 to manage all user and group accounts in New York. Delegate User2 to manage all user and group accounts in Seattle. </p><p><b>Technical requirements:</b> </p><p>Delegated administrative permissions must be scoped to specific locations. Minimize administrative effort and cost whenever possible. ==================== </p></td></tr>
<tr><td colspan="1" rowspan="2" valign="top"><b>URL:</b> </td><td colspan="5" valign="top">[https://docs.microsoft.com/en-us/azure/active-directory/roles/administrative-units](https://docs.microsoft.com/en-us/azure/active-directory/roles/administrative-units) </td></tr>
<tr><td colspan="5"></td></tr>
</table>


<br/>

[Return to top](#top) | [Back to main](./README.md)

<br/>



### Question # 15 (Multiple Choice) 

**Answer the following question based on the information presented in the case study.** 

You need to implement the planned changes for Disk1. What should you do first? 

1. Add ContosoSub1 and ContosoSub2 to a new management group. 
1. Remove Lock1 from ResourceGroup1. 
1. Modify the RG:1 tag. 
1. Remove Lock2 from ResourceGroup2. 



<table><tr><th colspan="1" valign="top"><b>Answer:</b>  </th><th colspan="19" valign="top">B </th></tr>
<tr><td colspan="1" valign="top"><b>Objective:</b>  </td><td colspan="19" valign="top">1\.3 Manage subscriptions and governance </td></tr>
<tr><td colspan="1" rowspan="13" valign="top"><b>Rationale:</b> </td><td colspan="19" valign="top"><p>To move a resource between resource groups, you need to first remove any locks associated with the resource. Disk1 has an inherited lock from ResourceGroup1. To move Disk1 you must first remove the lock.  </p><p>ResourceGroup2 has a Delete lock. However, this will not affect the ability to move or create resources in this resource group.  </p><p>Adding ContosoSub1 or ContosoSub2 to a new Management group has no relevance to the planned changes for Disk1. </p><p>Modifying the RG:1 tag will have no effect on the ability to move Disk1. ===================== </p><p><b>From the Case Study:</b> </p><p><b>Azure Environment:</b> </p><p>Contoso has two Azure subscriptions named <b>ContosoSub1</b> and <b>ContosoSub2</b>. <b>ContosoSub1</b> has the following resource group: </p></td></tr>
<tr><td colspan="5" valign="top"><b>Name</b> </td><td colspan="3" valign="top"><b>Lock name</b> </td><td colspan="4" valign="top"><b>Lock type</b> </td><td colspan="4" valign="top"><b>Region</b> </td></tr>
<tr><td colspan="5" valign="top">ResourceGroup1 </td><td colspan="3" valign="top">Lock1 </td><td colspan="4" valign="top">Read Only </td><td colspan="4" valign="top">West US </td></tr>
<tr><td colspan="2" valign="top"><b>ResourceGroup1</b> contains the following resources: </td></tr>
<tr><td colspan="3" valign="top"><b>Name</b> </td><td colspan="3" valign="top"><b>Type</b> </td><td colspan="3" valign="top"><b>Tags</b> </td><td colspan="4" valign="top"><b>Address space</b> </td><td colspan="4" valign="top"><b>Region</b> </td></tr>
<tr><td colspan="3" valign="top">Disk1 </td><td colspan="3" valign="top">Managed disk </td><td colspan="3" valign="top">RG:1 </td><td colspan="4" valign="top">N/A </td><td colspan="4" valign="top">West US </td></tr>
<tr><td colspan="3" valign="top">Vnet1 </td><td colspan="3" valign="top">Virtual network </td><td colspan="3" valign="top">RG:1 </td><td colspan="4" valign="top">10\.40.0.0/20 </td><td colspan="4" valign="top">West US </td></tr>
<tr><td colspan="2" valign="top"><b>ContosoSub2</b> has the following resource group: </td></tr>
<tr><td colspan="5" valign="top"><b>Name</b> </td><td colspan="3" valign="top"><b>Lock name</b> </td><td colspan="3" valign="top"><b>Lock type</b> </td><td colspan="4" valign="top"><b>Region</b> </td></tr>
<tr><td colspan="5" valign="top">ResourceGroup2 </td><td colspan="3" valign="top">Lock 2 </td><td colspan="3" valign="top">Delete </td><td colspan="4" valign="top">East US </td></tr>
<tr><td colspan="2" valign="top"><b>ResourceGroup2</b> contains the following resources: </td></tr>
<tr><td colspan="1" rowspan="2" valign="top"></td><td colspan="3" valign="top"><b>Name</b> </td><td colspan="3" valign="top"><b>Type</b> </td><td colspan="3" valign="top"><b>Tags</b> </td><td colspan="4" valign="top"><b>Address space</b> </td><td colspan="4" valign="top"><b>Region</b> </td></tr>
<tr><td colspan="3" valign="top">Disk2 </td><td colspan="3" valign="top">Managed disk </td><td colspan="3" valign="top">RG:2 </td><td colspan="4" valign="top">N/A </td><td colspan="4" valign="top">East US </td></tr>
</table>




<table><tr><th colspan="1"></th><th colspan="1"></th><th colspan="1"></th></tr>
<tr><td colspan="1" rowspan="3" valign="top"><b>URL:</b> </td><td colspan="3" valign="top">[https://docs.microsoft.com/en-us/azure/azure-resource-](https://docs.microsoft.com/en-us/azure/azure-resource-manager/management/lock-resources?tabs=json)</td></tr>
<tr><td colspan="1" valign="top">[manager/management/lock-resources?tabs=json](https://docs.microsoft.com/en-us/azure/azure-resource-manager/management/lock-resources?tabs=json) </td></tr>
<tr><td colspan="1"></td></tr>
</table>


<br/>

[Return to top](#top) | [Back to main](./README.md)

<br/>


### Question # 16 (Multiple Choice) 

**Answer the following question based on the information presented in the case study.** 

Which storage accounts meet the technical requirements? 

1. ContosoStorage1 and ContosoStorage4 only 
1. ContosoStorage2 and ContosoStorage3 only 
1. ContosoStorage1 and ContosoStorage3 only 
1. ContosoStorage2 and ContosoStorage4 only 



<table><tr><th colspan="1" valign="top"><b>Answer:</b>  </th><th colspan="4" valign="top">C </th></tr>
<tr><td colspan="1" valign="top"><b>Objective:</b>  </td><td colspan="4" valign="top">2\.3 Configure Azure files and Azure Blob Storage </td></tr>
<tr><td colspan="1" rowspan="7" valign="top"><b>Rationale:</b> </td><td colspan="4" valign="top"><p>Lifecycle management policies apply rules to supported storage accounts to control the transition of data to cooler storage tiers. Lifecycle management policies are supported for block blobs and append blobs in general-purpose v2, premium block blob, and Blob Storage accounts. FileStorage and general purpose v1 storage accounts do not support lifecycle management. </p><p>===================== </p><p><b>From the Case Study:</b> </p><p><b>Azure Storage Environment:</b> </p><p>ContosoSub1 contains the following storage accounts: </p></td></tr>
<tr><td colspan="2" valign="top"><b>Name</b> </td><td colspan="1" valign="top"><b>Kind</b> </td></tr>
<tr><td colspan="2" valign="top">ContosoStorage1 </td><td colspan="1" valign="top">StorageV2 (general purpose v2) </td></tr>
<tr><td colspan="2" valign="top">ContosoStorage2 </td><td colspan="1" valign="top">FileStorage </td></tr>
<tr><td colspan="2" valign="top">ContosoStorage3 </td><td colspan="1" valign="top">BlockBlobStorage </td></tr>
<tr><td colspan="2" valign="top">ContosoStorage4 </td><td colspan="1" valign="top">Storage (general purpose v1) </td></tr>
<tr><td colspan="1" valign="top"><p><b>Technical requirements:</b> </p><p>===================== </p></td></tr>
<tr><td colspan="1" rowspan="2" valign="top"><b>URL:</b> </td><td colspan="4" valign="top">[https://docs.microsoft.com/en-us/azure/storage/blobs/lifecycle-management-](https://docs.microsoft.com/en-us/azure/storage/blobs/lifecycle-management-overview)</td></tr>
<tr><td colspan="4" valign="top">[overview](https://docs.microsoft.com/en-us/azure/storage/blobs/lifecycle-management-overview) </td></tr>
</table>


<br/>

[Return to top](#top) | [Back to main](./README.md)

<br/>



### Question # 17 (Multiple Choice) 

**Answer the following question based on the information presented in the case study.** 

You need to address the issue that relates to ContosoStorage2. The solution must meet the security requirements. 

What should you do? 

1. Set a rotation reminder for the access keys. 
1. Configure a lifecycle management rule. 
1. Create a new access review. 
1. Generate a shared access signature (SAS). 



<table><tr><th colspan="1" valign="top"><b>Answer:</b>  </th><th colspan="4" valign="top">D </th></tr>
<tr><td colspan="1" valign="top"><b>Objective:</b>  </td><td colspan="4" valign="top">2\.1 Secure storage </td></tr>
<tr><td colspan="1" rowspan="7" valign="top"><b>Rationale:</b> </td><td colspan="4" valign="top"><p>A shared access signature (SAS) provides secure delegated access to resources in your storage account. You can use a SAS to provide granular control such as how long access is valid, what permissions they have to the resources, and what resources the client may access. </p><p>===================== </p><p><b>From the Case Study:</b> </p><p><b>Azure Storage Environment:</b> </p><p>ContosoSub1 contains the following storage accounts: </p></td></tr>
<tr><td colspan="2" valign="top"><b>Name</b> </td><td colspan="1" valign="top"><b>Kind</b> </td></tr>
<tr><td colspan="2" valign="top">ContosoStorage1 </td><td colspan="1" valign="top">StorageV2 (general purpose v2) </td></tr>
<tr><td colspan="2" valign="top">ContosoStorage2 </td><td colspan="1" valign="top">FileStorage </td></tr>
<tr><td colspan="2" valign="top">ContosoStorage3 </td><td colspan="1" valign="top">BlockBlobStorage </td></tr>
<tr><td colspan="2" valign="top">ContosoStorage4 </td><td colspan="1" valign="top">Storage (general purpose v1) </td></tr>
<tr><td colspan="1" valign="top"><p><b>Problem Statement:</b> </p><p><b>Security Requirements:</b> </p><p>Storage account access keys must not be directly shared with users.  ===================== </p></td></tr>
</table>




<table><tr><th colspan="1" rowspan="3" valign="top"><b>URL:</b> </th><th colspan="1" valign="top">[https://docs.microsoft.com/en-us/azure/storage/common/storage-sas-](https://docs.microsoft.com/en-us/azure/storage/common/storage-sas-overview?toc=/azure/storage/blobs/toc.json)</th></tr>
<tr><td colspan="1" valign="top">[overview?toc=/azure/storage/blobs/toc.json](https://docs.microsoft.com/en-us/azure/storage/common/storage-sas-overview?toc=/azure/storage/blobs/toc.json) </td></tr>
<tr><td colspan="1"></td></tr>
</table>


<br/>

[Return to top](#top) | [Back to main](./README.md)

<br/>



### Question # 18 (Multiple Choice) 

**Answer the following question based on the information presented in the case study.** 

You need to implement the planned changes for Vnet1 and Vnet2. What should you do first? 

1. Move Vnet1 to the East US Azure region. 
1. Move Vnet2 to the ContosoSub1 subscription. 
1. Modify the tag for Vnet2 
1. Modify the address space for Vnet1. 



<table><tr><th colspan="1" valign="top"><b>Answer:</b>  </th><th colspan="19" valign="top">D </th></tr>
<tr><td colspan="1" valign="top"><b>Objective:</b>  </td><td colspan="19" valign="top">4\.1 Implement and manage virtual networking </td></tr>
<tr><td colspan="1" rowspan="14" valign="top"><b>Rationale:</b> </td><td colspan="19" valign="top"><p>The virtual networks you peer must have non-overlapping IP address spaces. As shown in the case study Vnet1 and Vnet2 have overlapping IP address spaces. Because of this, you will need to modify the address space for one of the virtual networks. You can peer virtual networks from different regions and from different subscriptions, and so A and B do not address the issue. </p><p>Modifying the tag for Vnet2 does not address the issue. ===================== </p><p><b>From the Case Study:</b> </p><p><b>Azure Environment</b> </p><p>Contoso has two Azure subscriptions named <b>ContosoSub1</b> and <b>ContosoSub2</b>. <b>ContosoSub1</b> has the following resource group: </p></td></tr>
<tr><td colspan="5" valign="top"><b>Name</b> </td><td colspan="3" valign="top"><b>Lock name</b> </td><td colspan="4" valign="top"><b>Lock type</b> </td><td colspan="4" valign="top"><b>Region</b> </td></tr>
<tr><td colspan="5" valign="top">ResourceGroup1 </td><td colspan="3" valign="top">Lock1 </td><td colspan="4" valign="top">Read Only </td><td colspan="4" valign="top">West US </td></tr>
<tr><td colspan="2" valign="top"><b>ResourceGroup1</b> contains the following resources: </td></tr>
<tr><td colspan="3" valign="top"><b>Name</b> </td><td colspan="3" valign="top"><b>Type</b> </td><td colspan="3" valign="top"><b>Tags</b> </td><td colspan="4" valign="top"><b>Address space</b> </td><td colspan="4" valign="top"><b>Region</b> </td></tr>
<tr><td colspan="3" valign="top">Disk1 </td><td colspan="3" valign="top">Managed disk </td><td colspan="3" valign="top">RG:1 </td><td colspan="4" valign="top">N/A </td><td colspan="4" valign="top">West US </td></tr>
<tr><td colspan="3" valign="top">Vnet1 </td><td colspan="3" valign="top">Virtual network </td><td colspan="3" valign="top">RG:1 </td><td colspan="4" valign="top">10\.40.0.0/20 </td><td colspan="4" valign="top">West US </td></tr>
<tr><td colspan="2" valign="top"><b>ContosoSub2</b> has the following resource group: </td></tr>
<tr><td colspan="5" valign="top"><b>Name</b> </td><td colspan="3" valign="top"><b>Lock name</b> </td><td colspan="3" valign="top"><b>Lock type</b> </td><td colspan="4" valign="top"><b>Region</b> </td></tr>
<tr><td colspan="5" valign="top">ResourceGroup2 </td><td colspan="3" valign="top">Lock 2 </td><td colspan="3" valign="top">Delete </td><td colspan="4" valign="top">East US </td></tr>
<tr><td colspan="2" valign="top"><b>ResourceGroup2</b> contains the following resources: </td></tr>
<tr><td colspan="3" valign="top"><b>Name</b> </td><td colspan="3" valign="top"><b>Type</b> </td><td colspan="3" valign="top"><b>Tags</b> </td><td colspan="4" valign="top"><b>Address space</b> </td><td colspan="4" valign="top"><b>Region</b> </td></tr>
<tr><td colspan="1" rowspan="2" valign="top"></td><td colspan="3" valign="top">Disk2 </td><td colspan="3" valign="top">Managed disk </td><td colspan="3" valign="top">RG:2 </td><td colspan="4" valign="top">N/A </td><td colspan="4" valign="top">East US </td></tr>
<tr><td colspan="3" valign="top">Vnet2 </td><td colspan="3" valign="top">Virtual network </td><td colspan="3" valign="top">RG:2 </td><td colspan="4" valign="top">10\.40.0.0/22 </td><td colspan="4" valign="top">East US </td></tr>
</table>




<table><tr><th colspan="1"></th><th colspan="1" valign="top"><p><b>Planned Changes:</b> </p><p>Peering between Vnet1 and Vnet2. ===================== </p></th></tr>
<tr><td colspan="1" rowspan="2" valign="top"><b>URL:</b> </td><td colspan="1" valign="top">[https://docs.microsoft.com/en-us/azure/virtual-network/virtual-network-manage-](https://docs.microsoft.com/en-us/azure/virtual-network/virtual-network-manage-peering)</td></tr>
<tr><td colspan="1" valign="top">[peering](https://docs.microsoft.com/en-us/azure/virtual-network/virtual-network-manage-peering) </td></tr>
</table>


<br/>

[Return to top](#top) | [Back to main](./README.md)

<br/>

### Question # 19 (Multiple Choice) 

**Answer the following question based on the information presented in the case study.** 

Before you deploy DevVM1, you need to consider the technical and security requirements. What should you do to ensure that access to DevVM1 is secure? 

1. Install the Azure Virtual Desktop client on all the devices that will connect to DevVM1. 
1. Deploy the Azure Bastion service. 
1. Configure Remote Desktop Gateway on all the devices that will connect to DevVM1. 
1. Configure the Azure Network Watcher service. 



<table><tr><th colspan="1" valign="top"><b>Answer:</b>  </th><th colspan="1" valign="top">B </th></tr>
<tr><td colspan="1" valign="top"><b>Objective:</b>  </td><td colspan="1" valign="top">4\.2 Secure access to virtual networks </td></tr>
<tr><td colspan="1" valign="top"><b>Rationale:</b> </td><td colspan="1" valign="top"><p>Azure Bastion is a service that provides secure and seamless RDP/SSH connectivity to your virtual machines directly from the Azure portal over TLS. When you connect via Azure Bastion, your virtual machines do not need a public IP address, agent, or special client software. Not requiring a public IP address protects the virtual machine from outside port scanning. </p><p>===================== <b>From the Case Study: Planned Changes:</b> </p><p>Deploy a new Windows 10 Azure VM named DevVM1. <b>Technical requirements:</b> </p><p>DevVM1 must be accessible from the Azure portal over TLS and provide seamless RDP/SSH connectivity. </p><p><b>Security Requirements:</b> </p><p>DevVM1 must be protected from port scanning from outside the virtual network. ===================== </p></td></tr>
<tr><td colspan="1" rowspan="2" valign="top"><b>URL:</b> </td><td colspan="1" valign="top">[https://docs.microsoft.com/en-us/azure/bastion/bastion-overview](https://docs.microsoft.com/en-us/azure/bastion/bastion-overview) </td></tr>
<tr><td colspan="1"></td></tr>
</table>


<br/>

[Return to top](#top) | [Back to main](./README.md)

<br/>

### Question # 20 (Multiple Choice) 

**Answer the following question based on the information presented in the case study.** 

You need to resolve the issue that relates to the replication costs for backups. 

Which Recovery Services vault can be configured to use locally-redundant storage (LRS) replication? 

1. Rsv1 only 
1. Rsv2 only 
1. Rsv3 only 
1. Rsv1 and Rsv2 only 
1. Rsv1, Rsv2, and Rsv3 



<table><tr><th colspan="1" valign="top"><b>Answer:</b>  </th><th colspan="5" valign="top">C </th></tr>
<tr><td colspan="1" valign="top"><b>Objective:</b>  </td><td colspan="5" valign="top">5\.2 Implement backup and recovery </td></tr>
<tr><td colspan="1" rowspan="6" valign="top"><b>Rationale:</b> </td><td colspan="5" valign="top"><p>The storage replication type cannot be changed after protecting items. Since Rsv3 is the only Recovery services vault that does not contain items, it is the only one that can be modified to use the Locally-redundant storage replication type. </p><p>===================== </p><p><b>From the Case Study:</b> </p><p><b>Azure Storage Environment:</b> </p><p>Recovery service vaults have been configured as follows: </p></td></tr>
<tr><td colspan="2" valign="top"><b>Name</b> </td><td colspan="1" valign="top"><b>Backup contains:</b> </td><td colspan="1" valign="top"><b>Storage replication type:</b> </td></tr>
<tr><td colspan="2" valign="top">Rsv1 </td><td colspan="1" valign="top">Azure file shares </td><td colspan="1" valign="top">Geo-redundant </td></tr>
<tr><td colspan="2" valign="top">Rsv2 </td><td colspan="1" valign="top">Virtual machines </td><td colspan="1" valign="top">Geo-redundant </td></tr>
<tr><td colspan="2" valign="top">Rsv3 </td><td colspan="1" valign="top">No items </td><td colspan="1" valign="top">Geo-redundant </td></tr>
<tr><td colspan="1" valign="top"><p><b>Problem Statement:</b> </p><p>Replication costs for backups are over budget. </p><p><b>Planned Changes:</b> </p><p>Configure backups to use Locally-redundant replication when possible. ===================== </p></td></tr>
<tr><td colspan="1" rowspan="2" valign="top"><b>URL:</b> </td><td colspan="5" valign="top">[https://docs.microsoft.com/en-us/azure/backup/backup-create-rs-vault](https://docs.microsoft.com/en-us/azure/backup/backup-create-rs-vault) </td></tr>
<tr><td colspan="5"></td></tr>
</table>

