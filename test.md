<!--slide6-->
# Setup and manage VMs
## Azure Configuration & Automation



<!--slide7-->
# Configuration Demo Script (1)
## PowerShell in Azure Cloud Shell

* I can get a shell experience of my liking - **PowerShell** or **Bash** natively in the Azure Portal (or [full screen](https://shell.azure.com)) via the **Cloud Shell**. 
    * This essentially enables an authenticated shell experience from virtually anywhere.
  
* I can **easily navigate** all my Azure resources as if I am navigating filesystem. And I can take action against them using familiar PowerShell cmdlets
    * Your investment in PowerShell easily transfers from on-prem to the Cloud

<!--slide8-->
# Demo Overview
 ***Prework:*** *Open PowerShell from the drop-down in the Cloud Shell in the portal (before the session), wait for the prompt and close it. Opening again during the demo will be fast. Increase the font size through selector*
## Demo
1. Open PowerShell in Cloud Shell
2. List all the subscriptions
* **dir (or ls)**
3. Go to a specific subscription – ‘Contoso IT – demo’ and list the resources
* **cd con<tab>**
* **dir (or ls)** 
4. Go to VirtualMachines, list them and group them by location
* **cd vir<tab>** 
* **dir**
* **dir | group location**
5. List all the commands that are available to you
* **get-command | measure **
* **get-command**
6. Use existing commands to take actions (Azure drive allows easy navigation)
* **New-AzureRmResourceGroup –Name zMyRG –Location westus**
7. Easily open the Cloud Shell in full screen mode (no portal distractions)

