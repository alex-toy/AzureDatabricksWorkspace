# Azure Databricks Workspace

You can create an Azure Databricks Resource just like you do other resources in Azure. There are several items to configure that are common to other resources such as

- subscription name
- resource group name
- region

In addition, Azure Databricks is organized into workspaces and you will provide a workspace name when you create the resource.

There are several pricing tiers but the pricing in Azure Databricks is tied to access rather than processing power. Processing power affects pricing when you add compute resources to your Azure Databricks resource.

Hint: To view your DBFS files, enable the DBFS file browser in Databricks by going to Admin Console -> Workspace Settings -> Advanced

Hint: If you are going to use PySpark Pandas, make sure you create your Spark Cluster using a Databricks runtime >= 10.0

1. Create a **Worskspace**
<img src="/pictures/databricks-workspace.png" title="databricks workspace"  width="700">


2. Create a **Spark Cluster** in Databricks. Go to the Compute tab
<img src="/pictures/spark-cluster.png" title="spark clsuter"  width="700">


3. Read and Write Data in Databricks. Go to the create tab and choose shared / create / Notebook
<img src="/pictures/create-notebook.png" title="create notebook"  width="700">


3. In the **Data** tab, import your data in the *sparkify_log_small.json* file and create a new table.
<img src="/pictures/create-new-table.png" title="create new table"  width="700">
<img src="/pictures/created_table.png" title="created table"  width="700">


In order to see your data saved in the file system, you need to go to the Data / DBFS
<img src="/pictures/saved_data.png" title="saved data"  width="700">