# Lab 5 – Build a Database Server (AWS)

## Author

* **Name**: NIRANJAN S
* **Register Number**: 212224040221
* **Date of Submission**: 18/3/2026

---

## Objective

The objective of this experiment is to understand how to deploy and configure a database server in AWS. This lab focuses on launching an EC2 instance, installing a database management system (DBMS), configuring basic database settings, creating a sample database, and validating connectivity to the database server.

---

## Prerequisites

* Basic understanding of cloud computing concepts
* AWS account or AWS Academy Lab access
* An existing VPC and EC2 knowledge (from previous labs)
* Basic knowledge of Linux commands and SQL

---

## Tools Used

* AWS Management Console
* Amazon EC2
* Security Groups
* SSH Client (Terminal / PuTTY)
* MySQL / MariaDB / PostgreSQL (any one)

---

## Tasks Performed

### Task 1: Launch EC2 Instance for Database Server

Launch a new EC2 instance using Amazon Linux 2 AMI. Select an appropriate instance type and configure key pair and security group.

---

### Task 2: Configure Security Group for Database Access

Modify the security group to allow:

* SSH (Port 22) for remote access
* Database port (e.g., MySQL – 3306 or PostgreSQL – 5432)

---

### Task 3: Connect to EC2 Instance

Connect to the EC2 instance using SSH from your local machine.

---

### Task 4: Install Database Server

Install a database server software such as MySQL, MariaDB, or PostgreSQL on the EC2 instance using package manager commands.

---

### Task 5: Start and Configure Database Service

Start the database service and configure basic settings such as root password and user privileges.

---

### Task 6: Create a Sample Database

Create a sample database and a table inside it. Insert a few records into the table.

---

### Task 7: Test Database Connectivity

Test the database server by connecting to it locally or remotely and performing basic SQL queries.

---

## Workflow (Student Explanation)

(Write the steps you followed in your own words)

1.Logged into the AWS Management Console and launched a new EC2 instance using Amazon Linux 2 AMI, selected instance type, created key pair, and configured security group.
2.Modified the security group to allow SSH (port 22) and MySQL port (3306) for database access.
3.Connected to the EC2 instance using SSH from my local system using the key pair.
4.Installed the MySQL database server using package manager commands (sudo yum install mysql-server).
5.Started the MySQL service and enabled it, then secured the installation by setting a root password and configuring basic settings.
6.Created a sample database and table using SQL commands and inserted sample records.
7.Tested the database by running queries to retrieve data and verified that the database server was working correctly

---

## Output Screenshots (Attach 3)

### Screenshot 1: EC2 Instance for Database Server
<img width="1920" height="1080" alt="566162317-f701b3b3-31eb-4b1c-8508-812bd662516f" src="https://github.com/user-attachments/assets/f68bccce-3911-4768-a785-79a2405a8f11" />


---

### Screenshot 2: Database Service Running
<img width="1920" height="1080" alt="566162401-90e243a7-5125-49db-b61a-76dbf917e4b4" src="https://github.com/user-attachments/assets/004c2afe-93fb-4e03-ac29-1469deae4bfe" />



---

### Screenshot 3: Sample Database and Table

(Insert Screenshot Here)
<img width="1920" height="1080" alt="566162479-66975846-d3ab-4977-82d2-0f5c1c57c899" src="https://github.com/user-attachments/assets/7d930ff6-a26f-4ce1-b52f-af42fdf97818" />

---

## Result

This experiment demonstrated how to build a database server in AWS using an EC2 instance. By installing and configuring a DBMS, creating a sample database, and testing connectivity, the fundamentals of hosting and managing a cloud-based database server were underst
