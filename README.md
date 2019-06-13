# Terraform

An EC2 micro instance is created using Terraform. <br>
During the creation all the dependencies (Git,Docker, system updates) are created. <br>
A user for the developer is created, which has access to all the dependencies installed, but is not a super user. <br>
Accessing the server as dev should be possible with SSH, but without a .pem file, only by entering the password. 
