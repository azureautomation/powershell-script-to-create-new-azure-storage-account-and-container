Powershell Script to create new Azure Storage Account and Container
===================================================================

            

This script will create a new Azure Storage Account and Container. Azure Storage Account can have up to 500 TB of data, and we can have up to 100 Storage Accounts per Subscription (December 2014). Most importantly in my opinion is that Azure Storage
 Account has 20k IOPS limit. This is a lot, but must be considered when planning Azure deployments. At 500 IOPS per disk, this means we should keep a maximum of 40 disks in any given Storage Account. We should also keep other storage such as block blob storage
 in separate Storage Account.


To use this script, download it, adjust Script Execution Policy as needed, unblock the file, and dot source it like:




Output will look like:

![Image](https://github.com/azureautomation/powershell-script-to-create-new-azure-storage-account-and-container/raw/master/AzureStorage01.jpg) 






Code snippet:




 For more information see [http://superwidgets.wordpress.com/2014/12/11/creating-new-azure-storage-account-using-powershell/](http://superwidgets.wordpress.com/2014/12/11/creating-new-azure-storage-account-using-powershell/)






        
    
TechNet gallery is retiring! This script was migrated from TechNet script center to GitHub by Microsoft Azure Automation product group. All the Script Center fields like Rating, RatingCount and DownloadCount have been carried over to Github as-is for the migrated scripts only. Note : The Script Center fields will not be applicable for the new repositories created in Github & hence those fields will not show up for new Github repositories.
