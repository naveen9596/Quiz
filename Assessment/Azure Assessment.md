Here's a structured outline for an assignment focused on **Azure Storage Services** and **Azure SQL Database**. This assignment covers essential skills and concepts for working with these services in the cloud.

---

### **Azure Storage Services and Azure SQL Database Assignment**

#### **Objective:**
To gain hands-on experience with Azure Storage Services and Azure SQL Database, understand their features, and apply these technologies to manage data effectively in the cloud.

---

### **Part 1: Azure Storage Services**

#### **Tasks:**

1. **Set up a Storage Account**
   - Create an Azure Storage Account in the Azure portal.
   - Choose a storage replication option (e.g., LRS, ZRS, GRS) and explain the rationale behind your choice.
   - Explore available options and configuration settings in the Storage Account overview.

2. **Blob Storage**
   - Create a blob container within the Storage Account.
   - Upload various file types (text, image, video) to the container using the Azure portal.
   - Experiment with blob access tiers (Hot, Cool, Archive) and document the differences in cost and retrieval speed.
   - Generate a shared access signature (SAS) token for one of the blobs and demonstrate how to access the file using the SAS URL.

3. **File Storage**
   - Set up Azure File Storage within the Storage Account.
   - Mount the file share on your local system or a virtual machine in Azure.
   - Test reading/writing files to this share, and discuss potential use cases for Azure File Storage.

4. **Table and Queue Storage**
   - Create a Table Storage entity within the Storage Account.
   - Add some sample data (e.g., employee details, product catalog).
   - Set up a Queue Storage and add a few sample messages to the queue.
   - Explain scenarios where Table and Queue Storage would be preferred over SQL Database or other data storage types.

#### **Deliverables for Part 1:**
   - Screenshots and descriptions for each step.
   - A short write-up explaining use cases for Blob, File, Table, and Queue Storage.

---

### **Part 2: Azure SQL Database**

#### **Tasks:**

1. **Create an Azure SQL Database**
   - Set up an Azure SQL Database with a single database instance.
   - Configure database size, compute tier, and backup options, and explain the choices you made.
   - Explore the server firewall rules and configure access from your local IP address or a VM within the same Azure subscription.

2. **Database Operations**
   - Use SQL Server Management Studio (SSMS) or Azure Data Studio to connect to your Azure SQL Database.
   - Create a sample database schema with at least two tables (e.g., Customers and Orders).
   - Insert sample records into the tables and run basic SQL queries (SELECT, JOIN, UPDATE).

3. **Performance Tuning**
   - Configure indexing on one of the tables and test the query performance before and after indexing.
   - Explore Query Performance Insight in the Azure portal to monitor the performance of your queries.

4. **Data Security**
   - Enable Transparent Data Encryption (TDE) for the Azure SQL Database and discuss its benefits.
   - Configure auditing to log database activities and set up a storage account for audit logs.
   - Set up Azure Active Directory (AAD) authentication for database access (if applicable).

#### **Deliverables for Part 2:**
   - Screenshots and code snippets for each step.
   - A summary report on performance tuning and data security measures implemented.

---

### **Submission Guidelines:**

- **Format:** PDF report with screenshots, explanations, SQL code snippets, and answers to questions.
- **Naming Convention:** `[Your Name]_Azure_Storage_SQL_Assignment.pdf`
- **Due Date:** [Specify date]

---

### **Evaluation Criteria:**

- **Completeness:** Completion of all tasks with adequate screenshots and explanations.
- **Clarity:** Clear documentation of steps taken and rationale for chosen configurations.
- **Insight:** Understanding of Azure services, best practices in data storage, performance tuning, and security.

--- 

This assignment will help you build foundational skills in managing Azure's diverse storage solutions and databases, which are critical for data management in cloud environments. Good luck!
