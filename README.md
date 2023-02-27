# Overview

ADF pipelines can be use to ingest data from sources like CSV stored in blob storage into a Dataverse table. During the process of creating ADF pipelines we have encountered two scenarios which are documented in this repo with the code samples. One scenario talks about how data can be ingested from csv into a Dataverse table having lookup columns. Another scenario talks about the performance comparison of using DataFlow activity and Copy activity while ingesting data into Dataverse table.

## Scenarios

- [Inserting data into Dataverse table having referential columns using two pass operation.](././TwoPassOperation.md)
- [Performance overview of DataFlow or Copy activity to upsert data in Dataverse table.](./Performance%20comparision%20of%20Dataflow%20and%20Copy%20activity.md)
