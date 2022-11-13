Web Infrastructure Design
Project done during Full Stack Software Engineering studies at ALX. It aims to learn about how to design a Web Infrastructure.

Key concepts
Network basics
Server
Web server
Application server
DNS & DNS record types
Load Balancer
Monitoring
Database
Single point of failure
HTTP & HTTPS
Firewall
File Descriptions
Each file contains a link to an image hosted on Imgbox. These images are based on the following requirements:

0-simple_web_stack
On a whiteboard, design a one server web infrastructure that hosts the website that is reachable via www.foobar.com. Start your explanation by having a user wanting to access your website.

You must use:

1 physical server

1 web server (Nginx)

1 application server

1 application files (your code base)

1 database (MySQL)

1 domain name foobar.com configured with a www record that points to your server IP 8.8.8.8

1-distributed_web_infrastructure
On a whiteboard, design a three servers web infrastructure that host the website www.foobar.com.

You must add to 0-simple_web_stack:

2 physical servers

1 web server (Nginx)

1 application server

1 load-balancer (HAproxy)

1 application files (your code base)

1 database (MySQL)

2-secured_and_monitored_web_infrastructure
On a whiteboard, design a three servers web infrastructure that host the website www.foobar.com, it must be secured, serve encrypted traffic and be monitored.

You must add to 1-distributed_web_infrastructure:

3 firewalls

1 SSL certificate to serve www.foobar.com over HTTPS

3 monitoring clients (data collector for Sumologic or other monitoring services)

3-scale_up
You must add to 2-secured_and_monitored_web_infrastructure:

1 physical server

1 load-balancer (HAproxy) configured as cluster with the other one

Split components (web server, application server, database) with their own server

Files
Filename	Description
0-simple_web_stack	Web Infrastructure Design with a LAMP stack. This contains: 1 server, 1 web server, 1 application server, 1 database and 1 domain name
1-distributed_web_infrastructure	Web Infrastructure Design, based on 0-simple_web_stack that contains some additional components: 1 server, 1 web server, 1 application server, 1 load-balancer, 1 set of application files, 1 database
2-secured_and_monitored_web_infrastructure	Web Infrastructure Design, based on 1-distributed_web_infrastructure that contains some additional components: 3 firewalls, 1 SSL certificate, 3 monitoring clients
3-scale_up	Web Infrastructure Design, based on 2-secured_and_monitored_web_infrastructure that contains some additional components: 1 server, 1 load-balancer

General
You must be able to draw a diagram covering the web stack you built with the sysadmin/devops track projects
You must be able to explain what each component is doing
You must be able to explain system redundancy
Know all the mentioned acronyms: LAMP, SPOF, QPS
Copyright - Plagiarism
You are tasked to come up with solutions for the tasks below yourself to meet with the above learning objectives.
You will not be able to meet the objectives of this or any following project by copying and pasting someone else’s work.
You are not allowed to publish any content of this project.
Any form of plagiarism is strictly forbidden and will result in removal from the program.
Requirements
General
A README.md file, at the root of the folder of the project, is mandatory
For each task, once you are done whiteboarding (on a whiteboard, piece of paper or software or your choice), take a picture/screenshot of your diagram
This project will be manually reviewed:
As each task is completed, the name of that task will turn green
Upload a screenshot, showing that you completed the required levels, to any image hosting service (I personally use imgur but feel free to use anything you want).
For the following tasks, insert the link from of your screenshot into the answer file
After pushing your answer file to GitHub, insert the GitHub file link into the URL box
You will also have to whiteboard each task in front of a mentor, staff or student - no computer or notes will be allowed during the whiteboarding session
Focus on what you are being asked:
Cover what the requirements mention, we will explore details in a later project
Keep in mind that you will have 30 minutes to perform the exercise, you will get points for what is asked in requirements
Similarly in a job interview, you should answer what the interviewer asked for, be careful about being too verbose - always ask the interviewer if going into details is necessary - speaking too much can play against you
In this project, again, avoid going in details if not asked
