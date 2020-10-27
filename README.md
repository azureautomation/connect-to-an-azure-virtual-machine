Connect to an Azure Virtual Machine
===================================

            

**Description**


This PowerShell Workflow runbook sets up a connection to an Azure virtual machine. It requires the Azure virtual machine to have the Windows Remote Management service enabled, which is the default. It sets up a connection to the Azure
subscription and then imports the certificate used for the Azure VM so remote PowerShell calls can be made to it.  


**Requirements**


Before running this runbook, make sure the following Automation Assets and runbooks are available:


  *  An Automation credential asset containing the Azure Active directory Org Id username / password with access to this Azure subscription.


**Runbook Contents**


The runbook's contents are displayed below: 


 

 

        
    
TechNet gallery is retiring! This script was migrated from TechNet script center to GitHub by Microsoft Azure Automation product group. All the Script Center fields like Rating, RatingCount and DownloadCount have been carried over to Github as-is for the migrated scripts only. Note : The Script Center fields will not be applicable for the new repositories created in Github & hence those fields will not show up for new Github repositories.
