---
services: compute
platforms: java
author: selvasingh
---



# Getting Started with Compute - Manage Availability Set - in Java #

Compute Manage Virtual Machine Sample (for 1.0.0-beta2) - demonstrates how to perform common tasks using the Microsoft Azure Compute service.

   - Create an availability set
   - Create a virtual machine in a new availability set
   - Create another virtual machine in the same availability set
   - Update the availability set
   - Create another availability set
   - List availability sets
   - Delete an availability set.
 

## Running this Sample ##

To run this sample:

Set the environment variable `AZURE_AUTH_LOCATION` with the full path for an auth file. See [how to create an auth file](https://github.com/Azure/azure-sdk-for-java/blob/master/AUTH.md).

    git clone https://github.com/Azure-Samples/compute-java-manage-availability-sets.git

    cd compute-java-manage-availability-sets

    mvn clean compile exec:java

## More information ##

[http://azure.com/java] (http://azure.com/java)

[Virtual Machines](https://azure.microsoft.com/en-us/services/virtual-machines/)

[Virtual Machines - Learning Path](https://azure.microsoft.com/en-us/documentation/learning-paths/virtual-machines/)

[Manage the availability of virtual machines](https://azure.microsoft.com/en-us/documentation/articles/virtual-machines-windows-manage-availability/)

If you don't have a Microsoft Azure subscription you can get a FREE trial account [here](http://go.microsoft.com/fwlink/?LinkId=330212)

---

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.