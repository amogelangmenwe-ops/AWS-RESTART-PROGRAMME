

                                    In the AWS SimuLearn: Databases in Practice lab
-----------------------------------------------------------------------------------------------------------------------


I learned a lot about how real cloud-based databases operate and how much AWS simplifies tasks that would normally be very time-consuming. I got hands-on experience creating and configuring an Amazon RDS instance from scratch, which helped me understand how different settings—like instance class, storage type, security groups, and backup policies—affect database performance and reliability. I also gained a better understanding of monitoring tools such as CloudWatch, which allowed me to see how CPU usage, storage, and read/write activity change in real time. Working through these steps gave me a clearer sense of what it means to manage a production database environment and how important it is to plan for things like resilience, security, and failover.

In addition to basic setup and management, I learned how AWS uses features such as Multi-AZ deployments and read replicas to ensure high availability and scalability. Before this lab, I only had a general idea of what replication meant, but seeing how replicas are created and observing how the primary instance handles read and write operations gave me a much deeper understanding. It was interesting to learn how replicas can reduce the load on a primary database and improve performance for applications that have heavy read traffic. I also learned more about the behind-the-scenes processes—like how AWS handles replication lag and maintains data consistency across different instances. Altogether, the lab helped me appreciate how cloud-based databases are designed for both speed and reliability, and how these features can support real-world applications 🚀.

------------------------------------------------------------------------------------------------------------------------------
<img width="1284" height="482" alt="screenshot data" src="https://github.com/user-attachments/assets/0a65df57-0534-4ff0-98dc-93adc62ae74b" />



Challenge:
-

I struggled to create a new data replica during the lab, and the issue ended up being more confusing than I expected. At first, I couldn’t tell whether the problem was coming from the instance configuration, the region I selected, or the backup settings. The replica kept failing to initialize, and I wasn’t sure if it was because the primary instance didn’t have backups enabled, or if I had chosen an unsupported instance type for replication. I also found it challenging to navigate through all the RDS options since there were multiple settings that affected replication, such as storage type, version compatibility, and network access. On top of that, I initially didn’t notice an error message that pointed to insufficient permissions, which added to the confusion.

Solution: 
-
To solve the issue, I took a step back and reviewed the RDS requirements for creating read replicas. I checked that automated backups were enabled, verified the instance was in the correct region, and made sure the database engine version supported replication. I also reviewed the IAM permissions to confirm that my role allowed me to create replicas and modify RDS settings. After comparing my setup with the lab instructions and AWS documentation, I corrected the configuration by enabling the necessary features and adjusting the instance settings. Once everything was aligned, the replica finally launched successfully. This process taught me how important it is to double-check prerequisites and error messages instead of assuming the problem is technical when it might just be a missing configuration.
