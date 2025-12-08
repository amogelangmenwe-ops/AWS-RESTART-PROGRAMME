<img width="1320" height="602" alt="Screenshot 2025-12-03 203525" src="https://github.com/user-attachments/assets/e25b67cf-3e30-4047-bfed-dff5ec4c7249" />


                                 In the AWS SimuLearn: File Systems in the Cloud lab
---------------------------------------------------------------------------------------------------------------------------------
I learned how cloud-based file systems work and how Amazon EFS can provide scalable, shared storage for multiple EC2 instances. I got hands-on experience installing the necessary tools, such as amazon-efs-utils, and preparing the instance so it could communicate securely with the EFS mount target. Working through these steps helped me understand how EFS differs from traditional block storage like EBS, especially because EFS automatically scales and allows multiple machines to access the same data at the same time. I also began to see how useful EFS can be for applications that need shared storage, such as web servers, content management systems, or analytics workloads.

Another important thing I learned was how to mount an EFS file system using TLS for secure data transfer. The lab helped me understand the role of mount commands, DNS names, and the requirement for proper security group rules so the NFS protocol can function between an EC2 instance and an EFS mount target. I also gained confidence in verifying installation logs, checking dependencies such as stunnel, and confirming that everything was configured correctly before mounting. Overall, the process showed me how cloud file systems provide reliability, elasticity, and ease of use compared to traditional on-prem storage options 🔧.

Challenge:
-
One challenge I faced during the lab was trying to mount the EFS file system and running into repeated command errors. At one point, the terminal was telling me the command wasn't found, which made me think something was wrong with my syntax or the tools I installed. I also struggled with remembering the correct format of the EFS mount command, especially with the TLS option and the file system ID. Another issue was understanding whether the failure came from missing utilities, incorrect permissions, or security group restrictions. This made troubleshooting more complicated because even small mistakes—like an extra character or a missing package—caused the mount process to fail.

Solution: 
-
To resolve the problems, I went through each step slowly and verified everything one piece at a time. I reinstalled amazon-efs-utils and confirmed that stunnel was installed correctly since it is required for TLS connections. I also carefully corrected my mount command, making sure the file system ID and syntax matched the expected format. After that, I checked the instance’s security group rules to ensure NFS traffic (port 2049) was allowed from the EFS mount target. Once all the configurations lined up, the mount command finally worked and I could see the EFS directory on my instance. This process taught me how important accuracy is when working with file systems and how helpful systematic troubleshooting can be.
