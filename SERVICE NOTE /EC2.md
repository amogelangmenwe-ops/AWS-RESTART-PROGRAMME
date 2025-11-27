AMAZON EC2
=


1. Amazon EC2 (Elastic Compute Cloud) is a core AWS service that provides scalable, on-demand virtual servers in the cloud.EC2 enables users to launch and manage virtual servers in the cloud. These virtual machines, called instances, can run a wide variety of workloads, from simple web apps to complex enterprise applications, without the need to maintain physical hardware. It allows users to run applications without managing physical hardware, offering flexibility, scalability, and cost optimization. Below is a detailed explanation of each key EC2 topic:
   <img width="512" height="512" alt="image" src="https://github.com/user-attachments/assets/320f820c-2593-4878-b332-59a4fee6733f" />


>2. EC2 Instance Families

EC2 instances are grouped into families based on their performance characteristics and use cases. Families include general-purpose for balanced workloads, compute-optimized for CPU-heavy tasks, memory-optimized for large in-memory databases, and storage-optimized for high-performance storage needs.

>3. EC2 Instance Types 1 & 2

Within each family, EC2 offers different instance types that vary by CPU, memory, storage, and network performance. Choosing the right type ensures your workload gets optimal performance while controlling cost.

>4. Dedicated Hosts vs Dedicated Instances

Dedicated hosts provide an entire physical server dedicated to a single customer, useful for meeting compliance or licensing requirements. Dedicated instances run on shared hardware but remain isolated from other tenants, offering some level of isolation without the cost of a full host.

>5. EC2 Tenancy

Tenancy refers to whether your instance runs on shared or dedicated hardware. It affects cost, performance, and compliance, and users can choose per-instance tenancy to match their workload requirements.

>6. EC2 Pricing Models

EC2 pricing is flexible to accommodate different workloads. Users can pay for compute on-demand, reserve instances for long-term savings, or take advantage of spot instances for cost-sensitive, interruptible tasks.

>7. On-Demand Instances

On-demand instances are the simplest pricing model, allowing users to launch and terminate instances at any time without upfront payment. They provide maximum flexibility but are generally more expensive than reserved or spot instances.

>8. Reserved Instances (RI) 1 & 2

Reserved instances provide significant cost savings for long-term workloads in exchange for committing to a one- or three-year term. They come in standard and convertible types, with options for regional or zonal coverage, and help plan capacity and reduce cloud spend predictably.

>9. RI Limits & Capacity Reservations

RIs have limits on the number of instances per account and allow capacity reservations to ensure resources are available for critical workloads, even in high-demand periods.

>10. RI Marketplace

The RI Marketplace lets users buy or sell unused reserved instances. This provides flexibility to adjust reserved capacity as workload needs change while optimizing costs.

>11. Spot Instances

Spot instances let you use spare EC2 capacity at steep discounts. They are ideal for flexible, fault-tolerant workloads since AWS can reclaim these instances with little notice.

>12. Dedicated Pricing

Dedicated pricing applies to workloads that need complete isolation from other AWS customers. It ensures that the physical hardware is fully dedicated to a single tenant.

>13. Savings Plans 1 & 2

Savings Plans are flexible pricing models that provide cost savings in exchange for a commitment to consistent compute usage. Compute Savings Plans cover a wide range of services, while EC2 Savings Plans are specific to EC2 instances, helping reduce cloud costs effectively.
<img width="1240" height="480" alt="image" src="https://github.com/user-attachments/assets/ad1b7c35-996e-4385-9e0b-e0a66c0025ce" />

