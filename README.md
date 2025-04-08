Make a fork of this repo. 

Add secrets in repo settings > secrets
Create container registry in Azure.
Create a storage account in Azure
Create a fileshare in your storage account

* LOCATION (e.g. northeurope)
* REGISTRY_LOGIN_SERVER (***.azurecr.io)
* REGISTRY_PASSWORD (Either key in Access keys)
* REGISTRY_USERNAME (Account name as shown in Access keys)
* REPOSITORY_NAME (Name of this repo, if forked: "getting-started")
* RESOURCE_GROUP (Name of your Azure resource group)
* STORAGE_ACCOUNT_KEY (Either key in Access keys)
* STORAGE_ACCOUNT_NAME (Account name as shown in Access keys)
* SHARE_NAME (Your share's name)

Important!! The .yml file utilizes your resource group name for the DNS. This MUST be unique. Make sure the storage group name is unique, or change the value in the .yml file to correspond with a unique value. (at --dns-name-label)

Use the tutorial in Canvas to obtain your azure credentials and make sure the AZURE_CREDENTIALS secret exists. Good luck!
