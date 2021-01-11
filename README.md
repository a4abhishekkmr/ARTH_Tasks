# 18 👨🏻‍💻
Task Description📄

🔅 Create an AWS EC2 instance 

🔅 Configure the instance with Apache Webserver. 

🔅 Download php application name "WordPress".

🔅 As wordpress stores data at the backend in MySQL Database server. Therefore, you need to setup a MySQL server using AWS RDS service using Free Tier.

🔅 Provide the endpoint/connection string to the WordPress application to make it work


# 17 👨🏻‍💻
Task Description📄

🔅 Create your own Chat Servers, and establish a network to transfer data using Socket Programing by creating both Server and Clinet machine as Sender and Receiver both. Do this program using UDP data transfer protocol.

🔅 Use multi-threading concept to get and receive data parallelly from both the Server Sides. Observe the challenges that you face to achieve this using UDP. 

Note:  Machines must have different OS  like One Linux Machine one Windows. Both machines must be configured with python. 



# 16 👨🏻‍💻
Task Description📄

✔🔰 Research how Kubernetes is used in Industries and what all use cases are solved by Kubernetes?

📑  Create a blog/Article/video on industry use case for Kubernetes.


# 15 👨🏻‍💻
Task Description📄

✔🔅Create an ansible role myapache to configure Httpd WebServer.

🔅Create another ansible role myloadbalancer to configure HAProxy LB.

🔅We need to combine both of these roles controlling webserver versions  and solving challenge for host ip's  addition  dynamically over  each Managed Node  in  HAProxy.cfg file.


# 14 👨🏻‍💻
Task Description📄

✔🔰 14.1 Create a  network Topology Setup in such a way  so that System A can  ping to two Systems System B and System C but both these systems should not be pinging each other without using any security rule e.g firewall etc .

🔰 14.2 Further in ARTH - Task 10 have to create an Ansible playbook that will retrieve newContainer IP and update the inventory. So that further Configuration of Webserver could be done inside that Container.

🔰 14.3 Create an Ansible Playbook which will dynamically load the variable file named same as OS_name and just by using the variable names we can Configure our target node.( Note: No need to use when keyword here. )


# Task 13 👨🏻‍💻
Task Description📄

✔🔰 Create a Setup so that you can ping google but not able to ping Facebook from same system


# 12 👨‍💻
Task Description 📃

✔12.1 Use Ansible playbook to Configure Reverse Proxy i.e. Haproxy and update it's configuration file automatically on each time new Managed node (Configured With Apache Webserver) join the inventory.

12.2 Configure the same setup as 12.1 over AWS using instance over there.


# 11 👨🏻‍💻
Task Description📄

✔🔰 11.1 Configure Hadoop and start cluster services using Ansible Playbook

✔🔰 11.2 Create a Article, blog or Video on how industries are solving challenges using Ansible.

✔🔰 11.3 Restarting HTTPD Service is not idempotence in nature and also consume more resources suggest a way to rectify this challenge in Ansible playbook



# 10 👨🏻‍💻
Task Description📄

✔🔰Write an Ansible PlayBook that does the following operations in the managed nodes:
🔹 Configure Docker
🔹 Start and enable Docker services
🔹 Pull the httpd server image from the Docker Hub
🔹 Run the docker container and expose it to the public
🔹 Copy the html code in /var/www/html directory and start the web server


# 9 👨🏻‍💻
Task Description📄
✔🔰 Task 9.1 Create a Menu Using Voice Control in Python integrating all the concepts that have been taught by Vimal sir till now. 
✔🔰 Task 9.2 Create a Web Menu Using Python-CGI and API integrating all the concepts that have been taught by Vimal sir till now.

# 8 👨🏻‍💻
Task Description

✔🔰Create a Menu Using Python integrating all the concepts that have been taught by Vimal sir till now


# 7 👨🏻‍💻
 Description📄

7.1: Elasticity Task
🔹Integrating LVM with Hadoop and providing Elasticity to DataNode Storage
🔹Increase or Decrease the Size of Static Partition in Linux.
🔹Automating LVM Partition using Python-Script.

7.2: Docker Task
🔹Configuring HTTPD Server on Docker Container
🔹Setting up Python Interpreter and running Python Code on Docker Container
🔹Complete Task 7 must be performed within the respective teams allotted.


# 6 👨🏻‍💻
Task Description

✔🔰Create High Availability Architecture with AWS CLI
  The architecture includes-

- Webserver configured on EC2 Instance

- Document Root(/var/www/html) made persistent by mounting on EBS Block Device. - Static objects used in code such as pictures stored in S3

- Setting up Content Delivery Network using CloudFront and using the origin domain as S3 bucket.
- Finally place the Cloud Front URL on the webapp code for security and low latency.


# 5 👨🏻‍💻 
Task Description

✔🔰Explore the benefits which MNCs are getting from AI/ML and
 Create Blog/Article emphasizing the enhancement of AI provided to their products and make them the top notch companies of this generation.




# 4 👨🏻‍💻   
🔰Task 4.1 :- research and the world the know about the Myths of Hadoop

In a Hadoop cluster, find how to contribute limited/specific amount of storage as slave to the cluster?

Hint: Linux partitions

🔰Task 4.2 :- Team task:

According to popular articles, Hadoop uses the concept of parallelism to upload the split data while
fulfilling Velocity problem.

Research with your teams and conclude this statement with proper proof

Hint: tcpdump




# 3 👨🏻‍💻 
🔰Task 3.1 
- Setup a Hadoop cluster with one NameNode(Master) and 4 DataNodes(Slave) and one Client Node.
- Upload a file through client to the NameNode.

- Check which DataNode the Master chooses to store the file.

- Once uploaded try to read the file through Client using the cat command and while Master is trying
  to access the file from that DataNode where it stored the file delete that DataNode or crash it and see
  with help of the replicated storage how master retrieves the file and present it to client


✔🔰Task 3.2Description – AWS*
- Create a key pair

- Create a security group

- Launch an instance using the above created key pair and security group.

- Create an EBS volume of 1 GB.
 
- The final step is to attach the above created EBS volume to the instance you created in the previous steps.

- All the above steps must be performed using AWS CLI 


# 2 👨🏻‍💻 
✔🔰Read at least one case study or stories of companies that got benefitted from AWS according to your interest field and then create a blog/article of the same.


# 1 👨🏻‍💻 
✔🔰write a blog/Article on any Blogging site (Eg LinkedIn, Medium) that how big MNC’s




