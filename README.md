# Anypoint Partner Manager Payload Storage API - File Connector Example

> :warning: **Not for CloudHub Production**: This is for demo / example purposes only. Data stored to the file system on a CloudHub worker is not persistent. 

## Overview
Anypoint Partner Manager enables you to connect your own storage solution (such as a database, Amazon S3, Azure Blob Storage, and so on) to store the transmission content such as incoming and outgoing B2B message payloads. 

To store this content, you must implement an API that provides Anypoint Partner Manager with a standardized way to connect to your unique storage. You can follow read more [here](https://docs.mulesoft.com/partner-manager/2.0/setup-payload-storage-API) in the MuleSoft Documentation.

## Project
This Mule application is an example of the [Anypoint Partner Manager Payload Storage API](https://docs.mulesoft.com/partner-manager/2.0/setup-payload-storage-API). It uses the [File Connector](https://docs.mulesoft.com/file-connector/1.3/) and stores the data to the Mule application `src/main/resources` folder either in CloudHub or on-premises.

The table below shows the storage that is available depending on the worker size in CloudHub.

| Worker Size        | Storage           |
| ------------- |:-------------:| 
| 0.1 vCores      | 8 GB | 
| 0.2 vCores      | 8 GB      |
| 1 vCores      | 12 GB | 
| 2 vCores      | 40 GB      |

## Resources
* https://docs.mulesoft.com/partner-manager/2.0/setup-payload-storage-API
* https://www.mulesoft.com/exchange/com.mulesoft.b2b/partner-manager-content-storage-api



---

* Author: dejim.juang@mulesoft.com
* Updated Date: August 13, 2020

