# Run Databricks Job From Azure Data Factory (Or Synapse) using Pipelines

This code is based on the following blog post, with an addition of Job Fail Check at the end of the pipeline:<br>
[Leverage Azure Databricks jobs orchestration from Azure Data Factory - Microsoft Community Hub](https://techcommunity.microsoft.com/t5/analytics-on-azure-blog/leverage-azure-databricks-jobs-orchestration-from-azure-data/ba-p/3123862)<br>
Please refer to this blog to understand how the pipeline works.

## How to use the template?
Download the "Run Databricks Job.json" file and do one of the followings:
1. If you have Git configured on your Azure Data Factory (or Synapse workspace): put the file under the "pipeline" folder.
2. If not: copy the content of the downloaded file, create a new pipeline in your ADF or Synapse workspace with the name "Rub Databricks Job" from the portal, click on "View the JSON code representation of this resource" button from the top right corner of the workspace, paste the copied code, and save the changes.
