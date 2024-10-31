# Azure-Virtual-Desktop
----------------------------------------------------------------------------------------
This repository contains the FSLogix Configuration Steps for User Profile Management.
----------------------------------------------------------------------------------------
AVD Accelarator: https://github.com/Azure/avdaccelerator 
---------------------------------------------------------------------------------------
URL for Accessing AVD Session: aka.ms/avdweb
--------------------------------------------------------------------------------------
URL for downloading RD Client App: https://go.microsoft.com/fwlink/?linkid=2139369 
--------------------------------------------------------------------------------------
URL for downloading FSLogix: aka.ms/fslogix_download
--------------------------------------------------------------------------------------
URL for Installing the AVD Agents:
--------------------------------------------------------------------------------------
https://query.prod.cms.rt.microsoft.com/cms/api/am/binary/RWrmXv                                                                 
https://query.prod.cms.rt.microsoft.com/cms/api/am/binary/RWrxrH
-------------------------------------------------------------------------------------
Troubleshoot common Azure Virtual Desktop Agent issues:
https://learn.microsoft.com/en-us/azure/virtual-desktop/troubleshoot-agent#error-session-host-vms-are-stuck-in-upgrading-state
--------------------------------------------------------------------------------------------------------------------------------
Reinstall the agent and boot loader:
https://learn.microsoft.com/en-us/azure/virtual-desktop/troubleshoot-agent#step-4-reinstall-the-agent-and-boot-loader
---------------------------------------------------------------------------------------------------------------------------------
Download AzFiles Hybrid Module:
https://learn.microsoft.com/en-us/azure/storage/files/storage-files-identity-ad-ds-enable
https://github.com/Azure-Samples/azure-files-samples/releases
------------------------------------------------------------------------------------------------------------------------------------
MSRD Collect Tool for Troubleshooting AVD Issues
MSRD-Collect
Please download the latest MSRD-Collect tool from  https://aka.ms/MSRD-Collect
Copy the file to the affected machine and extract the content into a folder such as C:\MSDATA
While logged in on the affected machine, open an elevated PowerShell console, go to the folder with the script and execute:
 
.\MSRD-Collect.ps1
 
Confirm if you accept the EULA and if you agree with the data collection
If update is suggested, download the update and use that version. (if so, follow above steps again with new version)
Select the desired data collection scenario. (AVD + Target + Profiles +)
Wait until the script finishes collecting all data.
The script will automatically archive the collected data into a .zip file located in the C:\MSDATA folder. Please upload this .zip file to the workspace. You can also review the contents of the .zip file before uploading it.








