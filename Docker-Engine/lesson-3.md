#### 1) Running Container
     docker run -it alpine:latest sh  

#### 2) Go Back to terminal from running container. Note:   (Container will be running)
     PRESS ctrl + p + q

#### 3) Container Listing    
     docker container ls
     docker ps  
     docker container ls -a
     docker ps -a


#### 4) if you go back to running container first lisiting and copy container id or name your container Note: (90990 is your container id)
     docker exec -it 90990 sh


##  Exit Concept   

###### if you run a container first time and type exit the container will be stopped
###### but if you press p+q and go back the container will be running form
###### suppose you go back again in the same running container which you came out press p+q
###### And then you type exit the container will not be stopped it only stop in first time before you type p+q

#### 5) Docker Container stop
     docker container stop 90990

#### 6) Starting a stop Container 
     docker container star 90990

#### 7) Removing  Container Note: (First we stop the container then remove it) 
     docker container rm 90990

#### 8) Running Container in Detach Mode or run Container in Background
     docker container run -d  alpine:latest  

#### 9) Publish port
     docker container run -d -p 4000:80 alpine:latest  

#### 10) Custom container name (we use = or space both working same )
    docker container run -d --name=my_container -p 4000:80 alpine:latest  
    docker container run -d --name my_container -p 4000:80 alpine:latest  
