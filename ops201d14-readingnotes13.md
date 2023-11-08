# Reading notes 13

How has virtualization evolved beyond desktops and servers?

Virtualization is now used to create virtual versions of IT resources like networks, storage, and data devices. This makes it possible to create more flexible and efficient IT resources.

In the context of the Amazon IaaS Cloud Service Model, what does EC2 stand for?

In the context of the Amazon IaaS Cloud Service Model, EC2 stands for Amazon Elastic Compute Cloud. EC2 is a web service that provides on-demand virtualized servers.

What types of storage does EC2 use, and how is EC2 web traffic managed?

EC2 has two types of storage:
1) ephemeral (temporary) storage: the default storage for EC2 instances and it disappears when the instance is terminated
2) EBS (Elastic Block Storage): a more persistent form of storage that can be attached to multiple instances.

EC2 web traffic is managed using different of methods including:
1) load balancing: distributes web traffic evenly across multiple EC2 instances
2) routing: directs traffic to the appropriate instance based on the user's request.
3) CDNs (Content Delivery Networks): CDNs cache content closer to users to improve performance and reduce latency.

What are the benefits of service-oriented architecture for customers of EC2 virtualized services?

Service-oriented architecture (SOA) has multiple benefits including:

1) Standardization: SOA promotes the use of standardized interfaces and protocols, which makes it easier to integrate EC2 services with other applications and services.
2) Modularity: SOA allows services to be developed and deployed independently, which makes it easier to manage and update infrastructure.
3) Scalability: SOA makes it easier to scale EC2 services up or down to meet changing demand.

Analyze how cloud virtualization can promote equitable access to technology resources across diverse populations. How can this technology bridge cultural gaps and empower underserved communities?



source: https://www.joe0.com/2017/06/11/importance-of-virtualization-in-the-amazon-ec2-cloud/