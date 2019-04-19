# Open Data Sets example notebooks

This repository contains example notebooks demonstrating the [Open Data Sets](https://azure.microsoft.com/en-us/services/opendatasets/) Python SDK which allows you to enrich, and get open data sets using Azure.  The OpenDataSets SDK allows you the choice of using local or cloud compute resources, while managing and maintaining the complete data from the cloud.

## Quick installation
```sh
pip install azureml-contrib-opendatasets --index-url https://azuremlsdktestpypi.azureedge.net/sdk-release/master/588E708E0DF342C4A80BD954289657CF --extra-index-url https://pypi.python.org/simple
```

## How to navigate and use the example notebooks?

> * To use tutorials/enrich_demo_data_spark.ipynb, you should already have an Azure Subscription, and have created an
>   Azure Databricks Workspace. You should have installed pandas=0.23.0 (or above). Upload the notebook over there, and
>   clike 'Run'.

> * To use tutorials/enrich_demo_data.ipynb, either you already have a Azure Databricks Workspace, or you have your own
>   Jupyter server. Then you simply upload the notebook overthere, and run.


## Tutorials

The [Tutorials](./tutorials) forlder contains notebooks for the tutorials descrbied in the [Azure Machine Learning
SDk](https://review.docs.microsoft.com/en-us/python/api/azureml-contrib-opendatasets/?view=azure-ml-py&branch=dev-azureml).

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
