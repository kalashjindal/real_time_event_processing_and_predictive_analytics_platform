# Day 2-3: Infrastructure Setup 💻☁️

**Tasks:**

1. 🆔 Create an AWS account:
   - If you don't have one already, go to the AWS homepage and follow the steps to create a new account. You will need this to access AWS services like EC2.

2. 🚀 Provision three EC2 instances on AWS:
   - These instances will act as your servers for Apache Kafka (for data ingestion), Apache Spark (for data processing), and Apache Hadoop (for data storage). 
   - Choose the instance type based on the workload you expect for each service. For instance, if you're handling large volumes of data, you might need instances with more memory and processing power.

3. 🛠 Install Apache Kafka, Apache Spark, and Apache Hadoop:
   - SSH (Secure Shell) into each of the instances you created. This will give you a command-line interface for each instance.
   - Download and install Apache Kafka, Apache Spark, and Apache Hadoop on their respective instances.

4. 🌐 Set up networking:
   - Ensure that your instances can communicate with each other. This might involve setting up virtual private cloud (VPC) settings and ensuring that your instances are in the same VPC or are correctly peered if they're in different VPCs.

5. 🔒 Set up security groups:
   - Security groups act as a virtual firewall for your instances. 
   - Set up inbound rules (which control incoming traffic to your instances) and outbound rules (which control outgoing traffic from your instances) to ensure that only the necessary traffic is allowed.

**Study:**

📚 Here's what you should focus on learning today:

- AWS EC2 documentation:
  - Learn how to provision EC2 instances, how to SSH into them, and how to install software on them.

- Networking in AWS:
  - Learn about concepts like VPCs, subnets, and networking between EC2 instances.

- Security in AWS:
  - Understand how security groups work, how to set up inbound and outbound rules, and best practices for securing your EC2 instances.
