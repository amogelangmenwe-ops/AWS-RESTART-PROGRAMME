
                              In the AWS SimuLearn: Networking Concepts lab
------------------------------------------------------------------------------------------------------------------------------

I learned how different networking components work together inside AWS and how important they are for building secure, well-structured cloud environments. I worked with VPCs, subnets, route tables, and security groups, which helped me understand how traffic flows between different resources. Setting up private and public subnets showed me how AWS separates internal systems from those exposed to the internet, and configuring internet gateways and NAT gateways helped me see how instances can safely access external resources. The hands-on experience made networking feel much clearer and helped me see how each setting affects the overall architecture.

I also learned about network access control lists (NACLs), security group rules, and how they differ in terms of traffic filtering. Experimenting with inbound and outbound rules helped me understand how to protect resources and restrict unwanted access. The lab also taught me how DNS works in AWS through Route 53 and how load balancers distribute traffic across multiple instances. Seeing these components in action helped me appreciate how AWS networking is designed for both flexibility and security, and how these tools support real-world applications smoothly ⭐.

<img width="1281" height="578" alt="Screenshot 2025-12-04 121309" src="https://github.com/user-attachments/assets/eedc7c72-437e-42bf-88ec-e49e0a976850" />


Challenge:
-
One of the challenges I faced during this simulation was configuring the routing correctly. At first, I kept running into issues where my instances couldn’t connect to the internet or communicate with each other across subnets. I struggled to understand whether the problem was caused by the route table setup, missing gateway attachments, or subnet associations. The number of different networking components made it easy to overlook small details, and I also had trouble identifying which rule—NACL, security group, or route table—was blocking the traffic. This made troubleshooting more difficult than expected.

Solution:
-
To solve this, I went back through each networking component step by step. I checked that the route tables were associated with the correct subnets, ensured the internet gateway was properly attached to the VPC, and double-checked my security group and NACL rules to make sure nothing was accidentally blocking traffic. I also used the lab instructions to compare my configuration with the expected setup. Once I corrected the route table entries and fixed a missing outbound rule, everything started working as expected. This process taught me the importance of tracing network issues systematically and verifying each component instead of assuming the problem is isolated to one area.
