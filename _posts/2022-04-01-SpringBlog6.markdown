---
layout: post
title:  "Spring Blog 6"
date:   2022-04-01 11:23:20 -0700
categories: jekyll update
---
## This Blog will be about AWS Elastic Load Balancers (ELB) 
Below you will find out what a load balancer is and the benefits of using one!

# What is an Elastic  Load Balancer?
An EC2 load balancer spreads incoming application traffic across several EC2 instances in different Availability Zones. There is less risk of your applications failing if you do this. Elastic Load Balancing can tell when an instance is unhealthy and only sends traffic to healthy ones.

# The benefits of using an Elastic Load Balancer?
* Higher application performance - It can make your application run faster and do better work at a lower cost.
* Increased availability of application - The AWS ELB can handle traffic spikes and millions of requests at a time. Auto-scaling and load balancing rules provide seamless performance to users when traffic increases. The ELB uses the cloud’s agility and scalability to keep website traffic flowing.
* Security - Integrates SSL/TLS decryption, certificate management, and user authentication with Amazon Virtual Private Cloud (VPC). Together, they enable you to manage TLS settings centrally and offload CPU-intensive applications.

# Features of an Elastic Load Balancer 
* Health Monitoring - It can track unsuitable instances and balance the load towards the working instances.
* TLS Termination - SSL/TLS decryption and certificate management help the CPU from overloading.
* Layer 4 and 7 Balance - HTTP/HTTPS applications can load balance for layer 7 or just layer 4 which uses UDP and TCP.
