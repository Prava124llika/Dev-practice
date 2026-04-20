\# Linux User Creation and SSH Login (AWS EC2)



\## Task Name

User Creation and Password-Based SSH Login



\## Steps



1\. Connected to EC2 instance using SSH

2\. Switched to root user

3\. Created new user 'pravallika'

4\. Set password for user

5\. Enabled password authentication in sshd\_config

6\. Restarted SSH service

7\. Logged in using new user



\## Commands Used



useradd pravallika

passwd pravallika

vi /etc/ssh/sshd\_config

systemctl restart sshd

