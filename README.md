# Dask with Kubernetes and Helm on Azure

## Background

[Dask](https://dask.org/) is simply the best way to implement task parallelism in Python today - if you are going anything that vaguely looks like task farming then you probably should consider using it. There is a lot of material already online discussing its general awesomeness, so it is left as an exercise to the reader to use their favourite search engine to find domain specific examples of its use.

While you can use Dask to parallelise your code on a single multi-core computer you, you really want to use it distributed mode on a cluster if you are processing large datasets where there is lots of parallelism.

The [recommend route](http://docs.dask.org/en/latest/setup/cloud.html) for running Dask on Azure in distributed mode is deploying Dask with Kubernetes and Helm.

## Sprint objectives 
* Create a learning path for Dask with Kubernetes and Helm on Azure

### Learning prerequisites
* [Administer containers in Azure](https://docs.microsoft.com/en-us/learn/paths/administer-containers-in-azure/)

### Update from sprint a DASK deployment for Cycle cloud 

The following resource was created see [Cloud Cloud Dask Deployment](https://github.com/research-software-reactor/cyclecloud/tree/master/CycleCloudProjects)

Please follow https://github.com/research-software-reactor/cyclecloud/blob/master/QuickStarts/SettingUpCycleCloud.md to setup Azure Cycle Cloud
