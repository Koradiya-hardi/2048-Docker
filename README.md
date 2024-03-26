# 2048-Docker
In this  we will walk through the process of building the popular 2048 game using Docker containers. Docker provides an efficient and consistent environment for packaging, distributing and running applications, making it an ideal choice for deploying games.


Copy the DockerFile from the github repositry to your machine.
Now in terminal write the following commands:-
 1. For building the iamge write the following command
         docker build -t 2048-game.
2. this command with build the image
3. Now to view the game on the port we will wirte the following command:
       docker run -d -p 80:80 2048-game
4. Now we can view our project on localhost 80.

   
