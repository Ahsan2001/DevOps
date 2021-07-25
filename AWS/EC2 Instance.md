# AWS EC2 INSTANCE 
 
## [WATCH ME FIRST](https://www.youtube.com/watch?v=rddm7FtmtMg)
     
 
## Opening Instance in Windows By Following Below Steps:


#### 1) First Download Putty And Install it.
#### 2) Open PuTTYGen
#### 3) Search Your .pem File by Click _ALL Files_ 
#### 4) Then Load {.pem}  Files
#### 5) And Save as Private Key.
#### 6) Now Open PuTTY and write host name 
	ec2-user@"Your Public IPv4 DNS"
#### 7) Double Click SSH On Left Side of Your Window
#### 8) Then Click Auth And Browse You .ppk File 
#### 9) Check Authentication Parameters (Optional)
#### 10) Congratz :clap: Your Ec2 Instance Virtual Machine Are Now Open :star_struck: 

---


## Running Command One Time:


#### 1) Quick update for your instance
	sudo yum update -y
#### 2) Install Git in Your EC2 instance
	sudo yum install git -y
#### 3) Install Node Js
	sudo yum install -y gcc-c++ make
	curl -sL https://rpm.nodesource.com/setup_12.x | sudo -E bash -
	sudo yum install -y nodejs
---





