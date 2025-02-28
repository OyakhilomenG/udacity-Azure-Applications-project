# Write-up Template

### Analyze, choose, and justify the appropriate resource option for deploying the app.

*For **both** a VM or App Service solution for the CMS app:*
- *Analyze costs, scalability, availability, and workflow*
- *Choose the appropriate solution (VM or App Service) for deploying the app*
- *Justify your choice*

### Assess app changes that would change your decision.

*Detail how the app and any other needs would have to change for you to change your decision in the last section.* 



## My Analysis: Azure VM vs Azure App Service

### Azure Virtual Machines (VMs)

**Pros**:
- Full Control: Complete control over the OS, software, and configurations.
- Customizability: Ideal for specific configurations or unsupported software.
- Isolation: Dedicated environment for security and performance.

**Cons**:
- Management Overhead: Requires OS updates, security patches, and maintenance.
- Complexity: More complex to set up and manage.
- Cost: Can be more expensive, especially when idle.

### Azure App Service

**Pros**:
- Managed Service: Azure handles infrastructure, scaling, patching, and maintenance.
- Ease of Use: Simplifies deployment and management.
- Scalability: Built-in scaling features.
- Cost-Effective: More cost-effective for variable usage patterns.

**Cons**:
- Limited Control: Less control over the underlying infrastructure.
- Compatibility: May not support all required software or configurations.

### My choice:

For this project, I will be using **Azure App Service** due to its ease of use, managed infrastructure, and scalability. It allows for a more streamlined deployment process and reduces the management overhead, enabling us to focus on developing and deploying the application.