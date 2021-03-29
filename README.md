# packer-img-sequencing

Add the following secrets to your ADO pipeline.  This Service Principal you create should 
have read/write access to the resource group defined in the json file.

* AZURE_CLOUD: Public
* AZURE_SECRET: $(SP_PASSWORD)
* AZURE_CLIENTID: $(SP_CLIENTID)
* AZURE_SUBSCRIPTIONID: $(SP_SUBSCRIPTIONID)
* AZURE_TENANTID: $(SP_TENANTID)
* AZURE_LOCATION: $(AZURE_LOCATION)
