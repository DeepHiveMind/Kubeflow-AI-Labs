# Labs for Training and Serving TensorFlow Models with Kubernetes and Kubeflow on Azure Container Service (AKS)

<!-- ## [Learning Objectives](./learningObjectives.md)
## [Presentation Content](./presentationContent.md)
## [Room Organization](./roomOrganization.md) -->



## Content Summary

| | Module | Description |
| --- | --- | --- |
|0| **[Introduction](0-intro)** | Introduction to this workshop. Motivations and goals.|
|1| **[Docker](1-docker)** | Docker and containers 101.|
|2| **[Kubernetes](2-kubernetes)** | Kubernetes important concepts overview.|
|3| **[Helm](3-helm)** | Introduction to Helm |
|4| **[Kubeflow](4-kubeflow)** | Introduction to Kubeflow and how to deploy it in your cluster.|
|5| **[JupyterHub](5-jupyterhub)** | Learn how to run JupyterHub to create and manage Jupyter notebooks using Kubeflow |
|6| **[TFJob](6-tfjob)** | Introduction to `TFJob` and how to use it to deploy a simple TensorFlow training.|
|7| **[Distributed Tensorflow](7-distributed-tensorflow)** | Learn how to deploy and monitor distributed TensorFlow trainings with `TFJob`|
|8| **[Hyperparameters Sweep with Helm](8-hyperparam-sweep)** | Using Helm to deploy a large number of trainings testing different hypothesis, and TensorBoard to monitor and compare the results |
|9| **[Serving](9-serving)** | Using TensorFlow Serving to serve predictions |
|10| **[Going Further](10-going-further)** | Links and resources to go further: Autoscaling, Distributed Storage etc. |


## Prerequisites

1. Have a valid Microsoft Azure subscription allowing the creation of an AKS cluster
1. Docker client installed: [Installing Docker](https://www.docker.com/community-edition)
1. Azure-cli  (2.0) installed: [Installing the Azure CLI 2.0 | Microsoft Docs](https://docs.microsoft.com/en-us/cli/azure/install-azure-cli?view=azure-cli-latest)
1. Git cli installed: [Installing Git CLI](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)
1. Kubectl installed: [Installing Kubectl](https://kubernetes.io/docs/tasks/tools/install-kubectl/)
1. Helm installed: [Installing Helm CLI](https://docs.helm.sh/using_helm/#from-the-binary-releases) (**Note**: On Windows you can extract the `tar` file using a tool like 7Zip.)
1. ksonnet installed: [Installing ksonnet CLI](https://ksonnet.io/#get-started)


# Credit note

The credit for the soul of this repo goes to none other than Microsoft. My endeavor is to add to the cosmetics, and make it even more simplified.


```@Official
https://github.com/Azure/kubeflow-labs
```


