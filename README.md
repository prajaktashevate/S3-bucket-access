📌 Project Objective :-
=================================================================================================================================
The objective of this project is to securely enable and manage cross-account access to Amazon S3 buckets, allowing designated AWS accounts (external or internal to the organization) to access, read, or write to specific S3 buckets without compromising security or governance standards.


📌 Project Description:-
=====================================================================================================================================
This project aims to implement secure, scalable, and auditable cross-account access to Amazon S3 buckets between different AWS accounts. It facilitates controlled data sharing where an S3 bucket in one AWS account (Account A) can be accessed by users, applications, or services in another AWS account (Account B).

📌 Architecture Flow :-
=================================================================================================================================
Key Components Involved:
•	Account A (Bucket Owner): Owns the S3 bucket that needs to be shared.
•	Account B (Requester): Requires access to the S3 bucket in Account A.
•	IAM Roles and Policies: Manage permissions and authentication.
•	S3 Bucket Policy or Resource Policy: Defines who can access the bucket.

📌 Benefits of This Setup:-
===============================================================================================================================
✅ Secure Data Sharing

✅ Cost Efficient

✅ Centralized Data Management

✅ Scalability

✅ Auditability

✅ Fine-Grained Permissions

✅ Supports Multi-Tenant Models
