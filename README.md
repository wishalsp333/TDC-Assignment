# TDC-Assignment

Step 1:

Install Docker

Step 2:

Go to InitialApp/Simple_Flask_App directory and run the following command

docker build -t simple-flask-app .  
docker run -d -p 50:5000 --name flask-container simple-flask-app

Go to InitialApp/DemoApp directory and run the following command.

docker build -t simple-django-app .  
docker run -d -p 80:8000 --name django-container simple-django-app

Step 3:

Create (Distributed Publisher/Subscriber System with a Central Server)
GO TO DockerizedPubSubApp folder and run the following command

docker build -t pubsub-image:v1 
docker run -d -p 80:80 --name pubsub_central pubsub-image:v1

Step 4:

#Distributed Publisher/Subscriber System with distributed servers
#Go to DistributedPubSub folder and run the following command

docker-compose up

