# Write-up Template

### Analyze, choose, and justify the appropriate resource option for deploying the app.

*For **both** a VM or App Service solution for the CMS app:*
- *Analyze costs, scalability, availability, and workflow*
- *Choose the appropriate solution (VM or App Service) for deploying the app*
- *Justify your choice*

### Assess app changes that would change your decision.

*Detail how the app and any other needs would have to change for you to change your decision in the last section.* 

For my solution, I chose be App because it is generally more cost-effective for web applications due to their pay-as-you-go pricing model. In terms of scaling, VM involves adding more instances or upgrading to larger instances, which can be complex and time-consuming. It requires manual intervention or custom automation scripts. Given that I do not yet these functionalities, I opted for Web App. Furthermore, App Services provide built-in high availability and disaster recovery options, with minimal configuration required. They automatically distribute traffic across multiple instances and region. Given these considerations, App Service is more appropriate solution for deploying the CMS app. It offers cost-effective pricing, automatic scaling, high availability, and a simplified deployment workflow. 
