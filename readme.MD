terraform-docker-server
--------------------
This project contains Terraform code to create a virtual machine and install Docker on it.
The goal is to avoid manual setup and make the process repeatable using Infrastructure as Code.

What this project does
----------------------
•	Creates a server (for example on AWS EC2).
•	Installs Docker automatically.
•	Gives you the public IP so you can SSH and use Docker right away.
                    
Prerequisites
----------------
•	Terraform installed.
•	AWS CLI (or any cloud provider CLI) configured with credentials.
•	An SSH key pair.
