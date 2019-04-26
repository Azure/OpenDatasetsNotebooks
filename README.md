# Open Datasets Example Notebooks

This repository contains example notebooks demonstrating the [Open Datasets](https://azure.microsoft.com/en-us/services/opendatasets/) Python SDK which allows you to enrich, and get open datasets using Azure.  The OpenDataSets SDK allows you the choice of using local or cloud compute resources, while managing and maintaining the complete data from the cloud.

## Quick installation
```sh
pip install azureml-contrib-opendatasets
```

## How to navigate and use the example notebooks?

> * To learn more about Azure Open Datasets: https://docs.microsoft.com/azure/open-datasets/
> * How to load open datasets into your familiar Pandas/SPARK DataFrame: check out notebooks under [tutorials/data-access](./tutorials/data-access/).
> * How to join your own data with open datasets: check out notebooks under [tutorials/data-join](./tutorials/data-join/).


> * For Pandas version, either you already created your own Azure Notebooks library, or you have your own
>   Jupyter server. Then you simply upload the notebook over there to run it.

> * For SPARK version, you can create an Azure Databricks Workspace in your Azure subscription, upload the notebook over there, and click 'Run'. 
Alternatively, you can setup your own SPARK cluster and run it there. 

## API reference

Detailed API references are available [here](https://docs.microsoft.com/en-us/python/api/azureml-contrib-opendatasets/?view=azure-ml-py). 

## Known issues
* Some datasets have limitations on time range for each access using Pandas, to avoid long response time or memory errors. 
But you can find ways to load more in the tutorials if you have a powerful machine and accept longer loading time.
* enrich_customer_data_*() methods can be slow when there are a lot of distinct latitude + longitude to join with. One way for optimize is to reduce the distinct count in customer data. 


# Contributing

This project welcomes contributions and suggestions.  Most contributions require you to agree to a
Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us
the rights to use your contribution. For details, visit https://cla.microsoft.com.

When you submit a pull request, a CLA-bot will automatically determine whether you need to provide
a CLA and decorate the PR appropriately (e.g., label, comment). Simply follow the instructions
provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or
contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.
