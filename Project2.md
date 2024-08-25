# Setting up Multiple Static Websites on a Single Server Using Nginx Virtual Hosts
In this project, you will learn the concept of subdomains and hosting multiple websites on a single server using Nginx Virtual Host configuration.
## S/N	Project Tasks
1	Install and configure Nignx on a server
2	Create two website directories with two different website templates.
3	Create two subdomains
4	Add the IP of the server as A record to the two subdomains.
5	Configure the Virtual host to point two subdomains to two different website directories.
6	Validate the setup by accessing the subdomains.
7	Create a certbot SSL certificate for the root Domain.
8	Configure certbot on Nginx for two websites.
9	Validate the subdomain websites’ SSL using OpenSSL utility.
# Documentation
Ubuntu server was spinned up, elastic IP is been associate to my instance.   Note: taking refrence from Project1
## Install Nginx and Setup Website
**Execute the following commands.
sudo apt update
sudo apt upgrade
sudo apt install nginx
*Start your Nginx server by running the sudo systemctl start nginx command, enable it to start on boot by executing sudo systemctl enable nginx, and then confirm if it's running with the sudo systemctl status nginx command.
*Visit your instances IP address in a web browser to view the default Nginx startup page.
![pic](img/(img1).png)
* Template Downloaded from https://www.tooplate.com
* Right clicked and selected Inspect from the drop down menu
* Right clicked on the website name, select Copy and click on Copy link address.
![pic](img/(img2).png)