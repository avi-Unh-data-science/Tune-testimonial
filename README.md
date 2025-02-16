<h2>Automated-CVE-Database-and-Patch-Management-System</h2>

The goal of this project is to compile a database of common vulnerabilities and exposures, or CVEs, for various products and manufacturers.
For this project, I used Amazon Relational Database Service (RDS) to establish a My SQL database for storing CVS data. Python, the Azure Databricks platform, and web scraping methods were used to get this CVE data.
Azure Databricks uses a scheduled job to gather and update the database with new CVEs.
To enable security teams to verify and install the required security patches on the environment's assets depending on vendor and product, a basic webpage is built with HTML and the Flask framework and hosted on an AWS EC2 instance.
Skills: Amazon EC2 · Amazon Relational Database Service (RDS) · SQL · MySQL · Azure Databricks · Python (Programming Language)
