📄 Task 1 

Write an Ansible PlayBook that does the following operations in the managed nodes:
🔅 Configure Docker
🔅 Start and enable Docker services
🔅 Pull the httpd server image from the Docker Hub
🔅 Run the httpd container and expose it to the public
🔅 Copy the html code in /var/www/html directory and start the web server


📄 Task 2

Statement: Deploy Web Server on AWS through ANSIBLE!

🔅Provision EC2 instance through ansible.
🔅Retrieve the IP Address of instance using dynamic inventory concept.
🔅Configure the web server through ansible!


Optional : Write a playbook for testing of the tasks.

For Example: If the task is installation of httpd package then for checking the status of package, ansible has the module named as package_facts.
if u don't find any module then command module can be useful

📄 Task 3


🔅 Objective : Create an Ansible Playbook which will dynamically load the variable file named same as OS_name and just by using the variable names we can Configure our target node.( Note: No need to use when keyword here. )

⚠️ Note: Complete process have to be automated!

📄 Task 4 

Statement: Deploy a Load Balancer and multiple Web Servers on AWS instances through ANSIBLE!

🔅Provision EC2 instances through ansible.
🔅 Retrieve the IP Address of instances using the dynamic inventory concept.
🔅Configure the web servers through the ansible role.
🔅Configure the load balancer through the ansible role.
🔅The target nodes of the load balancer should auto-update as per the status of web servers.

Summary: One-Click Instance Launched, Web Servers provisioned and Load Balancer ready!
