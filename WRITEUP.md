# Write-up Template

### Analyze, choose, and justify the appropriate resource option for deploying the app.

*For **both** a VM or App Service solution for the CMS app:*
- *Analyze costs, scalability, availability, and workflow*
- *Choose the appropriate solution (VM or App Service) for deploying the app*
- *Justify your choice*

I decided to use an App service for the CSM project, because the provided GitHub repository was already programed in Python (one of the multiple languages supported), and also allows me to use a continuous deployment model using GitHub. The hardware limitations of an App service, such as a maximum of 14GB of memory and 4 vCPU cores per instance where not a problem for this project.

### Assess app changes that would change your decision.

*Detail how the app and any other needs would have to change for you to change your decision in the last section.* 

If I need to control of the underlying operating system or I’m using custom software to support the requirements of my project, then the Virtual Machines are usually better. When my application is not always running or we need more than 14GB of memory and 4 vCPU cores per instance are also Virtual Machines the right election.