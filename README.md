# Step-to-host-website-aws
Simple steps to host website on AWS.


## Step to host website on AWS
----------------------------------------------
1. Login to  AWS console
2. create ec2 machine
3. configure security group(ssh -22 for admin only)(80 - for normal traffic)
4. connect to ec2 machine
5. install httpd webserver in machine(used to run web app)

```
 sudo su
 yum update -y
 yum install httpd -y
 cd /var/www/html
 create website 
 service httpd start
```
6. access website from browser using ec2 public ip or DNS


# Final Result: 

![image](https://github.com/RitikPyCode/Step-to-host-website-aws/assets/69500530/c998d67b-9c34-4aba-984d-4e0c3ee88b32)


# Thanks!!

## Let's Connect on LinkedIn: 
```
https://www.linkedin.com/in/ritikktiwari/
```
### Till then keep learning, and keep exploring !! 
