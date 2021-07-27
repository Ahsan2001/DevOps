## Bind Mount Complete  Practical Step by Step


#### Bind Mount is Used For Application Backup
#### Your Application Container Deleted and you lost all your data 
#### In that situtation bind mount is very helpful for this problem
#### At the Time of Creating Your Application Container You used this command 
     
     docker run -it --name=my-app-container -v /home/ahsanshaikh/My-App-Backup:/App-data ahsansabir/my-application:latest sh
     
     
# Explainations 

#####  --name=my-app-container         
####  Your Container Name


##### /home/ahsanshaikh/My-App-Backup    
#### Your Local Machine Path from root user to your desire folder My-App-Backup is your new folder where your container data will be saved 


##### : 
### semicolon giving purpose that your giving path completed 


#### :/App-data
### After Semicolon you create a folder inside Your Container  App-data is you folder name inside your container 


#### ahsansabir/my-application:latest
### this is your complete image name




# Now 
#### You have multple files in your App-data folder which is inside your container 
#### Suppose You Lost Your Container 
#### The Advantages is using bind mount that you have backup of all your files  which is inside the container 



