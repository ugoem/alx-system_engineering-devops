# Web infrastructure design

![image](https://user-images.githubusercontent.com/24642339/221423495-c79471ea-8b5e-4c93-acc4-9414b99f107b.png)



# Requirements
## General
* A README.md file, at the root of the folder of the project, is mandatory
* For each task, once you are done whiteboarding (on a whiteboard, piece of paper or software or your choice), take a picture/screenshot of your diagram
* This project will be manually reviewed:
* As each task is completed, the name of that task will turn green
* Upload a screenshot, showing that you completed the required levels, to any image hosting service (I personally use imgur but feel free to use anything you want).
* For the following tasks, insert the link from of your screenshot into the answer file
* After pushing your answer file to GitHub, insert the GitHub file link into the URL box
* You will also have to whiteboard each task in front of a mentor, staff or student - no computer or notes will be allowed during the whiteboarding session
* Focus on what you are being asked:
* Cover what the requirements mention, we will explore details in a later project
* Keep in mind that you will have 30 minutes to perform the exercise, you will get points for what is asked in requirements
* Similarly in a job interview, you should answer what the interviewer asked for, be careful about being too verbose - always ask the interviewer if going into details is necessary - speaking too much can play against you
* In this project, again, avoid going in details if not asked

# Tast 0
<blockquote class="imgur-embed-pub" lang="en" data-id="a/bjzbYXg" data-context="false" ><a href="//imgur.com/a/bjzbYXg"></a></blockquote><script async src="//s.imgur.com/min/embed.js" charset="utf-8"></script>

# Requirements:

## You must add:
* 2 servers
* 1 web server (Nginx)
* 1 application server
* 1 load-balancer (HAproxy)
* 1 set of application files (your code base)
* 1 database (MySQL)

## You must be able to explain some specifics about this infrastructure:
* For every additional element, why you are adding it
* What distribution algorithm your load balancer is configured with and how it works
* Is your load-balancer enabling an Active-Active or Active-Passive setup, explain the difference between both
* How a database Primary-Replica (Master-Slave) cluster works
* What is the difference between the Primary node and the Replica node in regard to the application
* You must be able to explain what the issues are with this infrastructure:
* Where are SPOF
* Security issues (no firewall, no HTTPS)
* No monitoring
