# Day 14: Data Security 🔒🛡️

**Tasks:**

1. 📡 Secure your data in transit:
   - Implement SSL encryption for data being transferred between Kafka, Spark, and Hadoop. 
   - This ensures that even if someone intercepts the data, they can't understand it without the decryption keys.

2. 💾 Secure your data at rest:
   - Use Hadoop's built-in HDFS encryption to encrypt data stored in HDFS. 
   - This ensures that even if someone gains unauthorized access to the data storage, they can't understand the data without the decryption keys.

3. 🔑 Implement access control:
   - Use Hadoop’s built-in access control lists (ACLs) to control who can access your data. 
   - This allows you to explicitly define who can read, write, and execute data in HDFS.

4. 🚧 Review your AWS security groups:
   - Ensure that only necessary ports are open and only the required services can access your EC2 instances.
   - Tightening the security around your instances can greatly reduce the risk of unauthorized access.

**Study:**

📚 Here's what you should focus on learning today:

- Kafka and Hadoop documentation:
  - Understand how to implement SSL for data in transit and HDFS encryption for data at rest.

- AWS security documentation:
  - Learn about security groups in AWS EC2. 
  - Understand best practices for securing EC2 instances.

- Data security principles:
  - Understand why data security is important and the common techniques and protocols used in the industry.
