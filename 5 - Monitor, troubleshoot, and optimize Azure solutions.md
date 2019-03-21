# Monitor, troubleshoot, and optimize Azure solutions (15-20%)

## Develop code to support scalability of apps and services 
* Implement autoscaling rules and patterns 
    * [Best practices for Autoscale](https://docs.microsoft.com/en-us/azure/azure-monitor/platform/autoscale-best-practices)
    * [Quickstart: Create a virtual machine scale set in the Azure portal](https://docs.microsoft.com/en-us/azure/virtual-machine-scale-sets/quick-create-portal)
    * [Tutorial: Create a virtual machine scale set and deploy a highly available app on Windows with Azure PowerShell](https://docs.microsoft.com/en-us/azure/virtual-machines/windows/tutorial-create-vmss)
    * [Tutorial: Create a virtual machine scale set and deploy a highly available app on Linux with the Azure CLI](https://docs.microsoft.com/en-us/azure/virtual-machines/linux/tutorial-create-vmss)
* Implement code that handles transient faults
    * [Transient fault handling](https://docs.microsoft.com/en-us/azure/architecture/best-practices/transient-faults)
## Integrate caching and content delivery within solutions 
* Store and retrieve data in Azure Redis cache
    * [Quickstart: Use Azure Cache for Redis with a .NET application](https://docs.microsoft.com/en-us/azure/azure-cache-for-redis/cache-dotnet-how-to-use-azure-redis-cache)
    * [Quickstart: Create an ASP.NET web app](https://docs.microsoft.com/en-us/azure/azure-cache-for-redis/cache-web-app-howto)
* Develop code to implement CDNs in solutions
    * [Quickstart: Create an Azure CDN profile and endpoint using Resource Manager template](https://docs.microsoft.com/en-us/azure/cdn/create-profile-resource-manager-template)
    * [Tutorial: Add Azure CDN to an Azure App Service web app](https://docs.microsoft.com/en-us/azure/cdn/cdn-add-to-web-app)
* [Invalidate cache content (CDN or Redis)](https://docs.microsoft.com/en-us/azure/architecture/best-practices/caching)
## Instrument solutions to support monitoring and logging 
* Configure instrumentation in an app or service by using Application Insights
    * [Start monitoring your ASP.NET Web Application](https://docs.microsoft.com/en-us/azure/azure-monitor/learn/quick-monitor-portal)
    * [Monitor Azure App Service performance](https://docs.microsoft.com/en-us/azure/azure-monitor/app/azure-web-apps)
* [Analyze and troubleshoot solutions by using Azure Monitor](https://docs.microsoft.com/en-us/azure/azure-monitor/insights/solutions)
* Implement Application Insights Web Test and Alerts
    * [Creating an Application Insights Web Test and Alert Programmatically](https://azure.microsoft.com/en-us/blog/creating-a-web-test-alert-programmatically-with-application-insights/)