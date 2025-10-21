---
layout: default
title: 'Trainer demonstrations'
nav_order: 6
has_children: false
---

# Trainer demonstrations
{: .no_toc }


## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

<br/>

---

<br/>

## Learning Path 4: Administer Virtual Networking

<!-- Demonstrations -->


**Create a virtual network with PowerShell**

```powershell
New-AzResourceGroup -Name AzureVNET -Location = 'eastus2'

$vnet = @{
    Name = 'vnet-2'
    ResourceGroupName = 'AzureVNET'
    Location = 'eastus2'
    AddressPrefix = '20.0.0.0/16'
}

$virtualNetwork = New-AzVirtualNetwork @vnet

$subnet = @{
    Name = 'subnet-1'
    VirtualNetwork = $virtualNetwork
    AddressPrefix = '20.0.0.0/24'
}
$subnetConfig = Add-AzVirtualNetworkSubnetConfig @subnet

$virtualNetwork | Set-AzVirtualNetwork
```


<br/>

---

<br/>
