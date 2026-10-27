Cloud Computing Interview Questions and Answers

A collection of important cloud computing interview questions with concise answers.

1. What is cloud computing?

Cloud computing is the delivery of computing resources—such as servers, storage, databases, networking, and software—over the internet. Instead of owning and maintaining all the infrastructure, organizations can provision resources on demand and pay for what they use.

2. What are the main cloud service models?

- IaaS (Infrastructure as a Service): Provides virtual machines, storage, and networking. Customers manage the operating system and applications. Example: Amazon EC2.
- PaaS (Platform as a Service): Provides a managed platform for building and deploying applications. The provider manages the underlying infrastructure. Example: Google App Engine.
- SaaS (Software as a Service): Provides ready-to-use software over the internet. Example: Microsoft 365.

3. What are the main cloud deployment models?

- Public cloud: Provider-owned infrastructure shared by multiple customers.
- Private cloud: Infrastructure dedicated to one organization.
- Hybrid cloud: A combination of private infrastructure and public cloud.
- Multi-cloud: Use of services from more than one cloud provider.

4. What is virtualization?

Virtualization allows multiple isolated virtual machines to run on one physical server. A hypervisor manages the physical resources and allocates them to virtual machines, improving utilization and flexibility.

5. What is the difference between scalability and elasticity?

Scalability is the ability to handle increased workload by adding resources. Elasticity is the ability to automatically add or remove resources as demand changes, often in near real time.

6. What is the difference between horizontal and vertical scaling?

- Vertical scaling: Increase the capacity of one machine, such as by adding CPU or memory.
- Horizontal scaling: Add more machines or instances to distribute the workload.

Horizontal scaling is often preferred for highly available, distributed applications.

7. What are a cloud region and an availability zone?

A region is a geographic area where a cloud provider operates infrastructure. An availability zone (AZ) is an isolated location within a region, typically made up of one or more data centers. Deploying across multiple AZs can improve availability.

8. What is high availability?

High availability means designing a system to remain operational with minimal downtime. Common techniques include deploying across multiple availability zones, using load balancers, removing single points of failure, and monitoring system health.

9. What is disaster recovery, and how is it different from high availability?

High availability is designed to keep a service running during localized failures. Disaster recovery (DR) focuses on restoring service after a major disruption, such as a regional outage. Two important DR metrics are:

- RTO (Recovery Time Objective): How long it can take to restore service.
- RPO (Recovery Point Objective): How much data loss, measured in time, is acceptable.

10. What is a load balancer?

A load balancer distributes incoming requests across multiple servers or instances. It helps improve performance and availability, and can stop sending traffic to unhealthy instances.

11. What is auto-scaling?

Auto-scaling automatically adjusts the number or size of compute resources based on demand or rules, such as CPU usage or request volume. It can help maintain performance while avoiding unnecessary costs.

12. What is the difference between object, block, and file storage?

- Object storage: Stores data as objects with metadata; suitable for backups, media, and data lakes.
- Block storage: Provides raw storage volumes for virtual machines and databases.
- File storage: Provides shared files in a hierarchical folder structure.

13. What is a VPC or virtual network?

A Virtual Private Cloud (VPC) is a logically isolated network in a public cloud. It lets an organization define network ranges, subnets, routing, and access controls for its cloud resources.

14. What is the shared responsibility model?

The cloud provider and customer share responsibility for security. The provider generally secures the underlying cloud infrastructure; customers are responsible for securing what they configure and run, such as identities, data, applications, and network settings. The exact division depends on the service model.

15. How do you secure a cloud environment?

Use least-privilege access, multi-factor authentication, encryption in transit and at rest, secure network rules, patching, logging and monitoring, backups, and regular reviews of permissions and configurations.

16. What is IAM?

Identity and Access Management (IAM) controls who can access cloud resources and what actions they can perform. Good IAM practice uses roles and narrowly scoped permissions rather than sharing long-lived credentials or granting broad access.

17. What is serverless computing?

Serverless computing lets developers run code without managing the underlying servers. The cloud provider handles provisioning and scaling, and billing is often based on execution or resource consumption. “Serverless” still uses servers—the provider manages them.

18. What is the difference between containers and virtual machines?

A virtual machine includes a full guest operating system and runs on a hypervisor. A container shares the host operating-system kernel and packages an application with its dependencies. Containers are typically lighter and start faster; VMs provide stronger OS-level isolation.

19. How can an organization control cloud costs?

Right-size resources, shut down unused environments, use auto-scaling, monitor spending with budgets and alerts, select suitable storage tiers, and review usage regularly. Cost optimization should not compromise reliability or security requirements.

20. What is cloud migration?

Cloud migration is moving applications, data, or infrastructure from on-premises environments or another cloud to a cloud platform. It usually involves assessing dependencies, choosing a migration approach, planning data transfer, testing, and validating performance and security after the move.
