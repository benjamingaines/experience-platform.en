---
keywords: Experience Platform;home;popular topics
solution: Experience Platform
title: Azure Data Lake Storage Gen2 connector
topic: overview
---

# Azure Data Lake Storage Gen2 connector

Adobe Experience Platform provides native connectivity for cloud providers like AWS, [!DNL Google Cloud Platform], and [!DNL Azure], allowing you to bring your data from these systems.

Cloud storage sources can bring your own data into [!DNL Platform] without the need to download, format, or upload. Ingested data can be formatted as XDM JSON, XDM parquet, or delimited. Every step of the process is integrated into the Sources workflow. [!DNL Platform] allows you to bring in data from [!DNL Azure Data Lake Storage Gen2] (ADLS-Gen2) through batches.

## IP address allow list

The following IP addresses must be added to an allow list prior to working with source connectors. Failing to add your region-specific IP addresses to your allow list may lead to errors or non-performance when using sources.

### East US region

- `20.41.2.0/23`
- `20.41.4.0/26`
- `20.44.17.80/28`
- `20.49.102.16/29`
- `40.70.148.160/28`
- `52.167.107.224/28`

### West Europe region

- `13.69.67.192/28`
- `13.69.107.112/28`
- `13.69.112.128/28`
- `40.74.24.192/26`
- `40.74.26.0/23`
- `40.113.176.232/29`
- `52.236.187.112/28`

### Australia East

- `13.70.74.144/28`
- `20.37.193.0/25`
- `20.37.193.128/26`
- `20.37.198.224/29`
- `40.79.163.80/28`
- `40.79.171.160/28`

## Connect [!DNL Azure Data Lake Storage Gen2] to [!DNL Platform]

The documentation below provides information on how to connect [!DNL Azure Data Lake Storage Gen2] to [!DNL Platform] using APIs or the user interface:

### Using APIs

- [Create an ADLS-Gen2 connector using the Flow Service API](../../tutorials/api/create/cloud-storage/adls-gen2.md)
- [Explore a cloud storage system using the Flow Service API](../../tutorials/api/explore/cloud-storage.md)
- [Collect cloud storage data using the Flow Service API](../../tutorials/api/collect/cloud-storage.md)

## Using the UI

- [Create an ADLS-Gen2 source connector in the UI](../../tutorials/ui/create/cloud-storage/adls-gen2.md)
- [Configure a dataflow for a cloud storage connector in the UI](../../tutorials/ui/dataflow/batch/cloud-storage.md)