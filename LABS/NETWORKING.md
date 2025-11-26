# 📂 Project 3.1 NETWORKING 

                              LAB 263   Create Subnets and VPC 

In this lab, I learned how to design and configure a virtual network environment using Virtual Private Clouds (VPCs) and subnets. The main goal was to understand how to segment network resources, control IP address allocation, and manage connectivity between different parts of a network. This lab provided hands-on experience with creating VPCs, defining subnets, and understanding routing and network isolation concepts in a cloud or virtualized environment.

✔ Project Objectives

Understand the purpose of a VPC and how it isolates network resources.

Learn how to create subnets within a VPC to organize network traffic.

Assign IP address ranges to VPCs and subnets.

Explore routing between subnets and configuring access controls.

Understand the role of gateways and how they connect a VPC to the internet.

Gain practical experience with network segmentation for security and efficiency.

✔ What I Did

Created a new VPC and assigned it an IP address range.

Defined multiple subnets within the VPC for different network segments.

Configured routing tables to allow or restrict traffic between subnets.

Set up internet gateways to provide external connectivity where needed.

Verified the VPC and subnet configurations by checking IP ranges and routes.

Learned how network segmentation helps improve security and manageability.

<img width="1130" height="439" alt="Create Subnets 5" src="https://github.com/user-attachments/assets/7a8bd0c2-4c36-4494-819d-3927f2a47213" />




Difficulties Encountered

Understanding IP ranges: Calculating subnet masks and assigning correct IP ranges took careful planning.
Routing configuration: Setting up routing between subnets and to the internet required understanding how traffic flows.
Network isolation: Ensuring subnets were properly isolated while still allowing necessary communication was tricky at first.
Multiple steps: Creating VPCs, subnets, and gateways in the right order required attention to detail.

# 📂 Project 3.2
                            LAB 264  Networking resources for a VPC

 Overview

In this lab, I explored how to set up and manage networking resources within a Virtual Private Cloud (VPC). The focus was on understanding components like route tables, internet gateways, NAT gateways, and security groups, and how they work together to control traffic flow, connectivity, and security. The lab provided hands-on experience with configuring networking resources to create a functional, secure, and scalable cloud network environment.

✔ Project Objectives

Understand the purpose of networking resources in a VPC.

Learn how to attach and configure internet gateways to allow external access.

Explore route tables to control how traffic moves between subnets and the internet.

Understand NAT gateways for allowing outbound internet traffic from private subnets.

Learn about security groups and network ACLs to manage inbound and outbound traffic.

Gain practical skills in configuring VPC components to ensure connectivity and security.

✔ What I Did

Created and attached an internet gateway to the VPC for external connectivity.

Configured route tables to manage traffic flow between subnets and to the internet.

Set up NAT gateways to allow private subnets to access the internet securely.

Created and applied security groups to control inbound and outbound traffic.

Verified network configurations by testing connectivity between subnets and to external resources.

Learned how combining these resources ensures a secure, well-structured network.

Difficulties Encountered

Understanding traffic flow: It was initially challenging to visualize how packets move between subnets, gateways, and the internet.

Configuring route tables correctly: Assigning routes to the right subnets and gateways required careful planning.

Security rules: Writing security group rules that were secure yet functional took careful attention.

Multiple interdependent resources: Ensuring internet gateways, NAT gateways, and route tables all worked together correctly was tricky at first.                             
