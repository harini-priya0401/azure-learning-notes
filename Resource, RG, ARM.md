# Azure Resources, Resource Groups, and Resource Manager

## 🔹 Resource
- A **resource** is the **outcome of an Azure service** that you create and use.  
- Examples:  
  - Virtual Machine (VM) from the Compute service  
  - Storage Account from the Storage service  
  - App Service from the Web service  
  - Virtual Network (VNet) from the Networking service  
  - Key Vault from the Security service  

👉 In simple words, whenever you use an Azure service, the end result you get (like a VM or storage account) is called a **resource**.

---

## 🔹 Resource Group (RG)
- A **resource group** is a **container** that holds related Azure resources.  
- You can group resources that share the same lifecycle (e.g., resources for one application).  
- Example:  
  - An e-commerce app might have a VM, a database, and a storage account.  
  - All these can be placed inside **one resource group**.  

👉 Makes it easier to manage, monitor, apply policies, and delete resources together.

---

## 🔹 Resource Manager
- **Azure Resource Manager (ARM)** is the **deployment and management service** in Azure.  
- It provides a **consistent management layer** for creating, updating, and deleting resources.  
- Uses **ARM templates** (JSON files) or **Bicep** for Infrastructure as Code (IaC).  
- Benefits:  
  - Role-Based Access Control (RBAC)  
  - Tags for cost tracking  
  - Dependency handling (ensures resources are created in the right order)  

👉 ARM is the **brain** that controls how resources are deployed and managed in Azure.

---

## 🔗 How They Work Together
1. You create **resources** (VM, Storage, etc.) as outcomes of Azure services.  
2. Place them inside a **resource group** (logical container).  
3. Manage everything through **Azure Resource Manager**.  
