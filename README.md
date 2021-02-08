# packer-img-sequencing

Add the following secrets to your ADO pipeline.  This Service Principal you create should 
have read/write access to the resource group defined in the json file.

* AZURE_CLOUD: Public
* AZURE_SECRET: $(AZURE_CLIENTID_SECRET)
* AZURE_CLIENTID: $(AZURE_CLIENTID)
* AZURE_SUBSCRIPTIONID: $(AZURE_SUBSCRIPTIONID)
* AZURE_TENANTID: $(AZURE_TENANTID)
* AZURE_LOCATION: $(AZURE_LOCATION)
