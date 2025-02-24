# Write-up Template

### Analyze, choose, and justify the appropriate resource option for deploying the app.

*For **both** a VM or App Service solution for the CMS app:*
- *Analyze costs, scalability, availability, and workflow*
- *Choose the appropriate solution (VM or App Service) for deploying the app*
- *Justify your choice*

### Assess app changes that would change your decision.

*Detail how the app and any other needs would have to change for you to change your decision in the last section.* 

For my solution, the following were considered between a Virtual Machine and App Service:

Costs
•	App Service - are typically more cost-effective for web applications due to their pay-as-you-go pricing model. 
•	VM - usually cost more because you have to manage the underlying infrastructure, like OS updates, patches, and scaling. The costs can go up if you need bigger instances or more of them to handle increased load.

Scalability
•	App Service - provide automatic scaling options, allowing the application to handle varying loads without manual intervention. This makes it easier to manage and more flexible to depending on the demand.
•	VM - Scaling involves adding more instances or upgrading to larger instances, which can be complex and time-consuming. It needs manual intervention or custom automation scripts.

Availability
•	App Service: App Services offer built-in high availability and disaster recovery options with minimal configuration. 
•	VM -high availability requires setting up multiple instances and configuring load balancers. This can be complex and requires ongoing management.

Workflow
•	App Service - provide a simplified deployment workflow with integrated tools for CI/CD. This means it is easier to deploy and manage applications.
•	VM - Deploying and managing applications involves more steps, including setting up the OS, configuring the environment, and managing updates. This will require more technical expertise.

Given the analysis above, the App Service solution is more appropriate to use for this project. It offers cost-effective pricing, automatic scaling, high availability, and easier to deploy especially for a newbie like me.


Assessing App Changes
If the project were to require more resource-intensive tasks or requires specific software and OS versions that are not supported by App Service, then moving to a VM would be more suitable. Virtual Machine will be beneficial to use if we need to configure resources and other infrastructure components to meet specific needs.
