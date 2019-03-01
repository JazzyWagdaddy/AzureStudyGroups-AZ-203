# AZ-203: Develop Azure Infrastructure as a Service Compute Solutions (10-15%)

## Implement solutions that use virtual machines (VM)
* For the disks, focus on [encryption basics and how key vault is related](https://docs.microsoft.com/en-us/azure/security/azure-security-disk-encryption-windows)
* creating ARM templates - review the ARM templates in the [quickstart templates](https://github.com/Azure/azure-quickstart-templates/tree/master/101-vm-simple-linux)
* Provision VMs
  * [Quickstart: Create a Windows virtual machine in Azure with PowerShell](https://docs.microsoft.com/en-us/azure/virtual-machines/windows/quick-create-powershell)
  * [Quickstart: Create a Windows virtual machine with the Azure CLI](https://docs.microsoft.com/en-us/azure/virtual-machines/windows/quick-create-cli)
  * [Quickstart: Create a Linux virtual machine in Azure with PowerShell](https://docs.microsoft.com/en-us/azure/virtual-machines/linux/quick-create-powershell)
  * [Quickstart: Create a Linux virtual machine with the Azure CLI](https://docs.microsoft.com/en-us/azure/virtual-machines/linux/quick-create-cli)
  * [Create and manage Windows VMs in Azure using C#](https://docs.microsoft.com/en-us/azure/virtual-machines/windows/csharp)
* Create ARM templates 
  * [Create Azure Resource Manager template](https://docs.microsoft.com/en-us/azure/azure-resource-manager/how-to-create-template)
  * [Quickstart: Create Azure Resource Manager templates by using Visual Studio Code](https://docs.microsoft.com/en-us/azure/azure-resource-manager/resource-manager-quickstart-create-templates-use-visual-studio-code?tabs=CLI)
* Configure Azure Disk Encryption for VMs
  * [Encrypt virtual disks on a Windows VM](https://docs.microsoft.com/en-us/azure/virtual-machines/windows/encrypt-disks)
  * [How to encrypt a Linux virtual machine in Azure](https://docs.microsoft.com/en-us/azure/virtual-machines/linux/encrypt-disks)

## Implement batch jobs by using Azure Batch Services
* for batch jobs, focus on knowing [how to use the .NET SDK for creating jobs](https://docs.microsoft.com/en-us/azure/batch/quick-run-dotnet), setting them up, and executing.
* the [batch .NET quickstart](https://github.com/Azure-Samples/batch-dotnet-quickstart) is worth reviewing
* skim through [Azure CLI and how to manage batch resources](https://docs.microsoft.com/en-us/azure/batch/batch-cli-get-started)
* Manage batch jobs by using Batch Service API
  * [Overview of Batch APIs and tools](https://docs.microsoft.com/en-us/azure/batch/batch-apis-tools)
  * [Persist task data to Azure Storage with the Batch service API](https://docs.microsoft.com/en-us/azure/batch/batch-task-output-files)
  * [Persist job and task data to Azure Storage with the Batch File Conventions library for .NET](https://docs.microsoft.com/en-us/azure/batch/batch-task-output-file-conventions)
* Run a batch job by using Azure CLI, Azure portal, and other tools
  * [Quickstart: Run your first Batch job with the Azure CLI](https://docs.microsoft.com/en-us/azure/batch/quick-create-cli)
  * [Quickstart: Run your first Batch job in the Azure portal](https://docs.microsoft.com/en-us/azure/batch/quick-create-portal)
  * [Quickstart: Run your first Azure Batch job with the .NET API](https://docs.microsoft.com/en-us/azure/batch/quick-run-dotnet)
  * [Quickstart: Run your first Batch job with the Python API](https://docs.microsoft.com/en-us/azure/batch/quick-run-python)
* Write code to run an Azure Batch Services batch job
  * [Persist task data to Azure Storage with the Batch service API](https://docs.microsoft.com/en-us/azure/batch/batch-task-output-files)
  * [Use Azure Batch CLI templates and file transfer](https://docs.microsoft.com/en-us/azure/batch/batch-cli-templates)

## Create containerized solutions
* Know how to use the [CLI at least for basic management of ACR](https://docs.microsoft.com/en-us/azure/container-registry/container-registry-get-started-azure-cli)
* [Create an Azure Container Registry, create, prep, and push images to it](https://docs.microsoft.com/en-us/azure/container-instances/container-instances-tutorial-prepare-acr)
* Create an Azure Managed Kubernetes Service (AKS) cluster 
  * [Azure Kubernetes Service (AKS) (including the service principal option)](https://docs.microsoft.com/en-us/azure/aks/intro-kubernetes)
  * [Quickstart: Deploy an Azure Kubernetes Service (AKS) cluster using the Azure CLI](https://docs.microsoft.com/en-us/azure/aks/kubernetes-walkthrough)
  
* Create container images for solutions
  * [Tutorial: Create a container image for deployment to Azure Container Instances](https://docs.microsoft.com/en-us/azure/container-instances/container-instances-tutorial-prepare-app)
* Publish an image to the Azure Container Registry
  * [Tutorial: Deploy an Azure container registry and push a container image](https://docs.microsoft.com/en-us/azure/container-instances/container-instances-tutorial-prepare-acr)
* Run containers by using Azure Container Instance or AKS
  * [Tutorial: Deploy a container application to Azure Container Instances](https://docs.microsoft.com/en-us/azure/container-instances/container-instances-tutorial-deploy-app)
  * [Quickstart: Deploy an Azure Kubernetes Service (AKS) cluster using the Azure portal](https://docs.microsoft.com/en-us/azure/aks/kubernetes-walkthrough-portal) 
