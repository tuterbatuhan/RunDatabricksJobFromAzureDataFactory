# RunDatabricksJobFromAzureDataFactory

This code is based on the following blog post, with an addition of Job Fail Check at the of the pipeline:<br>
[Leverage Azure Databricks jobs orchestration from Azure Data Factory - Microsoft Community Hub](https://techcommunity.microsoft.com/t5/analytics-on-azure-blog/leverage-azure-databricks-jobs-orchestration-from-azure-data/ba-p/3123862)

## How to use the template?
Download the "Run Databricks Job.json" file and do one of the followings:
1. If you have Git configured on your Azure Data Factory (Or Synapse workspce), put the file under the "pipeline" folder.
2. If not, copy the content of the file, create a new pipeleine in your workspace with the name "Rub Databricks Job" from the portal, click on "View the JSON code representation of this resource" button from the top right corner of the workspace, paste the copied code, and save the changes.
