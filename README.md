# azure-basic-pipeline

A sequence of steps have been taken in order to create a delta lake gen 2 with its containers, a databricks connector and a databricks env.
A API call is used towards earthquake gov data website to retrieve data.
Using the medallion architecture a bronze and silver layer have been created.
The storage is external, using the delta lake gen 2 that is connected towards databricks.
These notebooks have been used at tasks and a triggered workflow (in databricks) is created as a job.

