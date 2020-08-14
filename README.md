# Anypoint Partner Manager Payload Storage API - File Connector Example
This Mule application is an example of the Anypoint Partner Manager Payload Storage API. It uses the File Connector and stores the data to the Mule application `src/main/resources` folder either in CloudHub or on-premises.

> :warning: **Not for CloudHub Production**: This is for demo and example purposes only. Data stored to the file system on a CloudHub worker is not persistent. 

Anypoint Partner Manager enables you to connect your own storage solution (such as a database, Amazon S3, Azure Blob Storage, and so on) to store the transmission content such as incoming and outgoing B2B message payloads. 

To store this content, you must implement an API that provides Anypoint Partner Manager with a standardized way to connect to your unique storage. You can follow read more [here](https://docs.mulesoft.com/partner-manager/2.0/setup-payload-storage-API) in the MuleSoft Documentation.


---

* Author: dejim.juang@mulesoft.com
* Updated Date: August 13, 2020

