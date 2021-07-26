##### 1) Creating Script
     touch simple.sh
    
##### 2) Open vi 
     vi simple.sh

##### 3) Write this script
     !#bin/bash
     echo my first name is : $1
     echo my last name  is : $2

##### 4) To execute script
     ./simple.sh Ahsan Shaikh


##### 5) File Permission
     0 no permission
     1 executable permisson
     2 write permission
     4 readable permission

##### 6) check file permission
     ls -l
-rw-rw-r-- 

##### 7) give permission (7 means give all permission 1,2,4 =7)
     chmod 777 simple.sh  

##### 8) remove permission (5 means give only permission 1 and 4 =5 )
     chmod 577 simple.sh  
     
##### 9) give permission to your folder (-R means recursive it will give permission all files inside your folder)
     chmod 777 -R foldername  
