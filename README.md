# Launch_app_on-EC2
# project_1_EC2_Deep_drive_Deploy_Jenkins on AWS

Project-#1 & #2: Manual and automated provisionning of a Web App on a local machine
This project sets up a web app in on a local machine using vagrant to configure the differnt servers on Virtualbox, these VMs interrract with each other via HTTP protocole. Users login to the site, their credentials are stored in the MySql database, each time data is fetched from the data base, a copy is cached in memcached offload the database from being overwhelmed with many reads, thus optimising data reads. RabbitMq is used to couple between the services.

Services involved:
-Linux  Centos 
-AWS Web services
-AWS EC2
-RabbitMQ
-Memcached
-MySql
-Wordpress


Prerequisites
- Oracle VM Virtualbox
- Vagrant
- Vagrant plugins (vagrant-hostmanager)
- Git bash or equivalent editor


Step 1: Get you Website
Get a Worpress template from  tooplate.com

Step 2: create your virtual Machine
mkdir /f/vargrant-vm/finance
vagrannt init eurolinux-vagrant/centos-stream-9
vagrant up
vagrant ssh 
