# Azure Arc Hands-on Labs


## Azure Arc Overview

For customers who want to simplify complex and distributed environments across on-premises, edge, and multi-cloud, Azure Arc enables deployment of Azure services anywhere and extends Azure management to any infrastructure.

   - Organize and govern across environments - Get sprawling Windows and Linux servers and Kubernetes clusters under control by centrally organizing and governing from Azure-across clouds, datacenters, and edge.
   - Manage Kubernetes Apps at scale - Deploy and manage Kubernetes applications across environments using DevOps techniques. Ensure that applications are consistently  deployed and configured at scale from source control.
   - Run Azure data services anywhere - Get the latest cloud innovation and automation, elastic scale, and unified management for data workloads that are running across hybrid infrastructure. Ensure consistency in data governance and security and manage costs efficiently.

## Azure Arc Hands-on Labs

The following labs provide you a quick and easy way to get started with Azure Arc through virtual environments that do not require any complex set-up or installations. For the purposes of these exercises, let’s consider Contoso, a large manufacturing organization. Their IT systems run Windows, Linux, Kubernetes, and SQL Servers across multiple locations, including on-premises datacenters, distribution centers and multiple public clouds. This poses operational challenges for Contoso. They’d like a consistent way to govern and operate across these disparate environments, ensure security across the entire organization, and enable innovation and developer agility (especially with their investments in cloud native practices), all while meeting regulatory and compliance requirements.

With Azure Arc, Contoso can unify inventory, governance, and compliance ensuring consistency for their entire IT landscape. They already take advantage of the core management capabilities such as tagging, update management, governance with Azure Policy, monitoring with Azure Monitor, security with Azure Security Center and Azure Sentinel and more provided by the Azure Resource Manager for their Azure workloads but would like to extend these same capabilities to their resources outside Azure. By onboarding their servers and Kubernetes clusters running outside Azure to Azure Arc, Contoso can take advantage of all the ARM capabilities mentioned above. In addition, with Azure Arc enabled Kubernetes, Contoso can guarantee Kubernetes deployments and app consistency through GitOps-based configuration management for their Kubernetes clusters in Azure, other clouds, and on-premises.

Leveraging Azure Arc enabled data services, Contoso is interested in implementing cloud-native, evergreen versions of SQL and PostgreSQL Hyperscale to reduce the management overhead and deploy their applications and databases anywhere with elastic scale.

Let’s take the journey together with Contoso and see how easy it is to accomplish all the above with Azure Arc.

Click on each of the scenarios below to see the specific instructions to do the lab :

**Hands-on Lab 1** :  In this lab, you’ll learn to onboard a virtual machine and Kubernetes cluster, both running on-premises, to Azure Arc, apply a few Azure Policies, enable monitoring, and alerts as well as Integrate Azure Security Center and Azure Sentinel to your on-premises resources. You’ll also be able to deploy a SQL Server on the VM, connect it to Arc and explore SQL Assessments for this resource.

**Hands-on Lab 2** :  In this lab, you’ll learn to deploy GitOps configurations to the Kubernetes cluster that you onboarded to Arc earlier and enable Azure Policy add-on for Kubernetes to the same cluster.

**Hands-on Lab 3** :  In this lab, you’ll leverage the same Arc enabled Kubernetes cluster from the previous labs to deploy the Azure Arc data controller, Azure SQL Managed Instance & Azure PostgreSQL Hyperscale.



