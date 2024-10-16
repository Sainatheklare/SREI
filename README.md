# SREI
SRE-Interviews
I am preparing the list of interview questions for SRE/PE role in this repository to help others to prepare for their interviews. Most of these questions are seen before during my interviews.

Please feel free to provide any suggestions either through the pull-request or an issue. Please feel free to add your interview questions in this repo.

Practical Coding Questions:
Design In-Memory File System
LFU cache
LRU cache
Insert Delete GetRandom O(1) - Duplicates allowed
Find Duplicate File in System
Find k most frequent words from a file
How to Sort a Large File
Subdomain Visit Count
Add and Search Word - Data structure design
Design Twitter
Question: Given a list of servers and ports write a script to check if you are able to connect on that port.
Question: Identify if there is a SQL injection in the given query. Cover all the corner cases. Basically it was string manipulation question. You just need to check the structure of string inside any double quotation. Databricks
Competitive Coding Questions:
Word Break Google
Question: Given a string with special character *. Replace all the stars in the given string by all the characters and generate all possible strings. Example: ab*d. Now generate strings like ab1d, ab2d, etc. Google
An array should be split into two halves such that sum of two arrays is same (order of elements should not be changed)
Linux troubleshooting
CPU is under high I/O. How to find the issue?

What can go wrong in the filesystem?

What if the system has no more inodes available?

How to increase your I/O?

How to tune I/O?

You can’t see your mounted filesystem. What can be the issue? etc.

Someone started forkbomb on your system how would you stop it? Google

How would you troubleshoot network communication between two servers?

Question: You are trying to run the command but it says no more PIDs available. What can be the reason? How will you solve the issue? Google

Try to think about it from every aspects. There can be following cases
1) ulimit for your user/group is set to very low. You can't create processes more than ulimit range.
2) Someone started fork bomb. There are no PIDs available actually.
3) All PIDs have specific fd in the file system. You are running out of inodes.
Unable to boot OS. What can be the issue?

System Internals
How do fork and exec work?
Linux booting process
What is swap memory?
Process memory layout
What is virtual memory?
Types of processes
What (really) happens when you type ls -l in the shell
What are the difference between external and internal kill command Google
What are the inbuilt Linux commands? Google
Difference between RSS and VSZ?
System Design
Design basic api rate limiter
How many machines do you need when you design an online photo uploading service?(Include SPOF, load balancer) Google
Design message passing system like kafka
Design distributed key-value pair system.
How would you shard SQL databases
Design storage system for tiny url website
Home Assignment
Scheduler Design Mesosphere
Resource Manager Databricks
Networking
Explain routing protocol. You can pick any routing protocol. 
