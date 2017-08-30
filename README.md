---
services: Search
platforms: java
author: milismsft
---

## Getting Started with Search - Manage Search Service - in Java ##


  Azure Search sample for managing search service.
   - Create a Search service resource with a free SKU
   - Create a Search service resource with a standard SKU, one replica and one partition
   - Create a new query key and delete a query key
   - Update the Search service with three replicas and three partitions
   - Regenerate the primary and secondary admin keys
   - Delete the Search service
 

## Running this Sample ##

To run this sample:

Set the environment variable `AZURE_AUTH_LOCATION` with the full path for an auth file. See [how to create an auth file](https://github.com/Azure/azure-sdk-for-java/blob/master/AUTH.md).

    git clone https://github.com/Azure-Samples/search-java-manage-search-service.git

    cd search-java-manage-search-service

    mvn clean compile exec:java

## More information ##

[http://azure.com/java](http://azure.com/java)

If you don't have a Microsoft Azure subscription you can get a FREE trial account [here](http://go.microsoft.com/fwlink/?LinkId=330212)

---

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.