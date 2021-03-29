# packer-img-sequencing

Add the following secrets to your ADO pipeline.  This Service Principal you create should 
have read/write access to the resource group defined in the json file.

* AZURE_CLOUD: Public
* AZURE_SECRET: $(SP-PASSWORD)
* AZURE_CLIENTID: $(SP-CLIENTID)
* AZURE_SUBSCRIPTIONID: $(SP-SUBSCRIPTIONID)
* AZURE_TENANTID: $(SP-TENANTID)
* AZURE_LOCATION: $(AZURE_LOCATION)
