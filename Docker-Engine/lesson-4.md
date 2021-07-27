#### Creating image
     docker build -t myapp .


#### And for pushing my image to docker hub
     docker image push myapp:latest
     
#### Note the above command  will give you error Because myapp isn't an official repository at github
#### We have 2 solution for this


#### 1) At the time of creating image use your username for example
     docker build -t ahsansabir/myapp:latest
     
#### 2) Second Option Using Tag Command
     docker tag myapp ahsansabir/myapp:latest
      
