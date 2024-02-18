# Write-up Template

### Analyze, choose, and justify the appropriate resource option for deploying the app.

*For **both** a VM or App Service solution for the CMS app:*
- *Analyze costs, scalability, availability, and workflow*
- *Choose the appropriate solution (VM or App Service) for deploying the app*
- *Justify your choice*

Table compare app service and virtual machine in azure
| Feature | App Service | Virtual Machine (VM) |
|---|---|---|
| Cost | Pay-per-use based on resource consumption, cost-effective for smaller projects | Fixed cost based on allocated resources, potentially higher for small projects |
| Scalability | Automatically scales up/down based on traffic | Manual scaling required, or use VM scale sets with added complexity |
| Availability | Built-in redundancy and disaster recovery for high availability | Requires configuring availability features like Azure Availability Zones |
| Workflow | Simplified configuration and built-in tools, easier to deploy and manage | Greater control over environment, but requires managing server software, runtime, and deployment |

I choosing a web app service over a virtual machine. Cost-wise, this project is small application and low traffic count so use app service would us saving cash, better for virtual machine is fixed cost based on allocated resources. Regarding scalability, this project is small in scale so if traffic increases it will not be significant. App Service will automatically scale up/down based on traffic, better for virtual machines that require manual scaling or use more complex VM scalers. High availability is built-in, so your users enjoy consistent uptime. And when it comes to scaling, the web app adapts to your needs effortlessly, avoiding the manual VM configuration struggles. The seamless integration with your GitHub repository allows for effortless deployment with just a few clicks. This streamlines your workflow significantly compared to the cumbersome setup and configuration of a VM. Furthermore, the web app service excels in simplicity and speed. Based on the costs, scalability, availability, and workflow analysis I chosed the web app service to deploy for my project article.

### Assess app changes that would change your decision.

*Detail how the app and any other needs would have to change for you to change your decision in the last section.* 

I would choose virtual machine when security requirements is for specific compliance needs or highly sensitive data, VM can provide deeper control over security configurations. Regarding scalability, the app service is good to choose if traffic increases it will not be significant , but significantly high or unpredictable traffic spikes the app service cannot be managed, VM might offer more granular control over scaling. Regarding complexity, if this project involves complex processing, machine learning, or custom software dependencies, VM might provide more flexibility. However, keep in mind the cost, management complexity when using virtual machine. If the above happens. I will change my decision about using a virtual machine.