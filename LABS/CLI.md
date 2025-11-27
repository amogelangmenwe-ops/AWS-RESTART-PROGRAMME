                               💻 The AWS Command Line Interface (CLI) 
                               
CLI is a super handy tool that lets you work with AWS services straight from your terminal. Instead of clicking around in the AWS Management Console, you can run commands to create resources, upload files, set up services, and automate tasks. It’s perfect for scripting, managing multiple environments, and getting repetitive tasks done much faster. Using the CLI also gives you a peek behind the scenes, giving you more control over your AWS setup—definitely a must-have skill for anyone working in the cloud.


Overview

In Lab 168, I got hands-on with the AWS CLI. Instead of relying on the console, I learned how to interact with AWS services directly from the terminal. The lab helped me understand how the CLI works, why it’s useful, and how it fits into cloud and DevOps workflows.
                                                    
                                                         Objectives

The main goal of this lab was to get comfortable using the AWS CLI.
I focused on:

Configuring the CLI with my access keys and default region

Using the terminal to check S3 buckets and EC2 instances

Understanding how IAM permissions affect what I can do

Learning how to troubleshoot common mistakes


                                                        What I Did

During this lab, I went through several steps to get everything working:

1. Making sure the AWS CLI was installed

I checked that the CLI was available on my system and ready to use.

2. Setting up the CLI

I entered my access key, secret key, region, and output format. This allowed my computer to authenticate with AWS.

3. Checking S3 buckets

I listed the S3 buckets in my account to confirm the CLI was working correctly.

4. Creating and reviewing an S3 bucket

I created a new S3 bucket and explored how to interact with it from the terminal.

5. Looking at EC2 instances

I retrieved information about EC2 instances in my region to see how the CLI displays AWS resources.

6. Confirming my identity and permissions

I checked which IAM user I was logged in as and what permissions I had.

                                                        Challenges I Faced

Like most labs, things didn’t go perfectly on the first try. Some of the challenges I ran into included:

1. Permission issues

A few commands failed because my IAM user didn’t have the required permissions. I resolved this by updating the policies.

2. Wrong region selected

At first, some resources didn’t show up simply because they were in a different region. Changing the region fixed it.

3. Access key problems

I had to make sure the keys were entered correctly. If they’re wrong or expired, the CLI won’t work.

4. S3 bucket naming rules

S3 bucket names have to be globally unique, so I had to adjust the name until AWS accepted it.

5. Possible MFA requirements

Some actions may not work if MFA is required, so it’s important to check whether additional authentication is needed.

                                                          Evidence (Screenshots)

<img width="796" height="269" alt="Screenshot 2025-11-27 104948" src="https://github.com/user-attachments/assets/3a1a7f8c-dde9-4cd2-8652-ec04d39ddf48" />
<img width="813" height="424" alt="Screenshot 2025-11-27 105030" src="https://github.com/user-attachments/assets/08b7ebb3-c84a-4811-a483-07a47c543818" />
<img width="787" height="480" alt="Screenshot 2025-11-27 105050" src="https://github.com/user-attachments/assets/5390be96-4844-495f-af23-f5c9b8e0e359" />
<img width="785" height="479" alt="Screenshot 2025-11-27 105102" src="https://github.com/user-attachments/assets/b634480b-6b63-4c81-8d5a-bb3fa756f514" />

<img width="788" height="507" alt="Screenshot 2025-11-27 105234" src="https://github.com/user-attachments/assets/cf32c1ef-95d5-48ae-ba7f-c649e3053be9" />

<img width="795" height="474" alt="Screenshot 2025-11-27 105245" src="https://github.com/user-attachments/assets/78f3b19e-a678-49ae-8fd6-d2b5c5993038" />
<img width="789" height="475" alt="Screenshot 2025-11-27 105301" src="https://github.com/user-attachments/assets/d8bf50f6-fa90-4eb9-87fd-067bf7256d62" />
<img width="784" height="504" alt="Screenshot 2025-11-27 105315" src="https://github.com/user-attachments/assets/231af331-3740-4c99-9eaa-7cbca6c03138" />

<img width="796" height="398" alt="Screenshot 2025-11-27 105327" src="https://github.com/user-attachments/assets/e4ad7910-47bf-4c22-9366-91021efa5233" />
<img width="765" height="533" alt="Screenshot 2025-11-27 105339" src="https://github.com/user-attachments/assets/8ca10307-c72e-4a69-84c3-4bf88346c1c5" />

Conclusion

Lab 168 was helpful for building confidence with the AWS Command Line Interface.
I learned how to configure the CLI, run basic AWS operations, and understand common errors. This lab gave me a good foundation for future cloud and DevOps tasks, where the CLI is often faster and more efficient than the console.
