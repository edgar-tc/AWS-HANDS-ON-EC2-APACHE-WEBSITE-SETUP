# AWS-HANDS-ON-EC2-APACHE-WEBSITE-SETUP
Hands-on projects in DevOps and cloud computing are key to gaining practical skills and understanding essential concepts. 
I recently worked on a project where I created an EC2 instance using the AWS Command Line Interface (CLI), without using the AWS Management Console. 
This method gave me a chance to experience the convenience and flexibility of automating cloud infrastructure. 
After setting up the instance, I installed the Apache web server and hosted a website, showcasing the entire web deployment process. 
In this blog post, I’ll share the steps I took and what I learned from this experience.

Here’s a quick overview:

Launched an EC2 Instance: Utilized the AWS CLI to create a t2.micro instance, leveraging the free tier and configuring it programmatically.

Connected via SSH: Accessed the instance securely using SSH with my key pair for further configuration.

Automated Apache Installation: Implemented a user-data script to update packages, install Apache, and start the service automatically.

Hosted a Website: Created a simple HTML page and served it through Apache, verifying the setup by accessing it via the instance’s public IP.
