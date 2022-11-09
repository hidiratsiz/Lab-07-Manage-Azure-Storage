# Lab-07-Manage-Azure-Storage


In this lab, I will:
 1. Provision the lab environment
 2. Create and configure Azure Storage accounts
 3. Manage blob storage
 4. Manage authentication and authorization for Azure Storage
 5. Create and configure an Azure Files shares
 6. Manage network access for Azure Storage

 ## Architecture diagram

<img src="https://github.com/hidiratsiz/Lab-07-Manage-Azure-Storage/blob/main/az104-task.png" width="500px" align="center">




We create the architectural structure indicated in the picture above

1. Resource groups
2. Virtual machines
3. Storage accounts

After creating the network we will have will be like the picture below


## az104-05-vnet0 |Virtual Network  Diagram

<img src="https://github.com/hidiratsiz/Lab-07-Manage-Azure-Storage/blob/main/az104-05-vnet0.png" width="900px" align="center">


## az104-07-rg0 | Resource visualizer


<img src="https://github.com/hidiratsiz/Lab-07-Manage-Azure-Storage/blob/main/az104-07-rg0.png" width="900px" align="center">



## Mount the Azure file share

Navigate to the storage account that contains the file share you'd like to mount.

Select File shares.
Select the file share you'd like to mount.
Select Connect.
Select the drive letter to mount the share to.
Copy the provided script and Paste the script into a shell on the host you'd like to mount the file share to, and run it.

You have now mounted your Azure file share.

<img src="https://github.com/hidiratsiz/Lab-07-Manage-Azure-Storage/blob/main/Mount-Azure-file-share.png" width="900px" align="center">

<img src="https://github.com/hidiratsiz/Lab-07-Manage-Azure-Storage/blob/main/Mount-Azure-file-share1.png" width="900px" align="center">

### Attach files to file share via Azure portal

<img src="https://github.com/hidiratsiz/Lab-07-Manage-Azure-Storage/blob/main/Adding-files-from-Azure.png" width="900px" align="center">

### Attach files to file share via VM


<img src="https://github.com/hidiratsiz/Lab-07-Manage-Azure-Storage/blob/main/vm-adding-file.png" width="900px" align="center">

### file sharing image in virtual machine
<img src="https://github.com/hidiratsiz/Lab-07-Manage-Azure-Storage/blob/main/lastscreen.png" width="900px" align="center">


##  Manage blob storage

In this task, you will create a blob container and upload a blob into it.

1.On the Storage account blade, in the Data storage section, click Containers.

2.Click + Container and create a container with the following images:


<img src="https://github.com/hidiratsiz/Lab-07-Manage-Azure-Storage/blob/main/containers.png" width="900px" align="center">

<img src="https://github.com/hidiratsiz/Lab-07-Manage-Azure-Storage/blob/main/containers-upload.png" width="900px" align="center">

<img src="https://github.com/hidiratsiz/Lab-07-Manage-Azure-Storage/blob/main/containers-upload1.png" width="900px" align="center">

<img src="https://github.com/hidiratsiz/Lab-07-Manage-Azure-Storage/blob/main/containers-upload3.png" width="900px" align="center">


Review
In this lab, you have:

Provisioned the lab environment
Created and configured Azure Storage accounts
Managed blob storage
Created and configured Azure Files shares
Managed network access for Azure Storage