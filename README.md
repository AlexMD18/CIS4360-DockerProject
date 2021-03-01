# CIS4360-DockerProject
### Partner: Maryam
The first part of the installation process was to download the Docker Desktop application from the official Docker website. Once the inital install was completed, a restart was required. After the restart was completed, it was required that I install WSL2 which included running several scripts through powershell that allowed me to install and update WSL to the latest version. Once these installs were completed, I was able to begin creating a container in Docker.

#### Part 1: Cloning a Repository
This repository was given to us by Docker which contained what was required to build an image and run it as a container.
![image](https://user-images.githubusercontent.com/60632552/109560518-fb5a6880-7aa9-11eb-86d4-7e6bd176864b.png)

#### Part 2: Building an Image
This step took a long time to complete as it installed all the files required to build the image and run the container.
![image](https://user-images.githubusercontent.com/60632552/109563324-9b65c100-7aad-11eb-94df-9044e024c777.png)

#### Part 3: Running the Container
In part 2, the image was created and built. Part 3 shows how to run the container that was just created. This was a simple command that told the docker to run the application on map port 80, host port 80, and the name of the application.
![image](https://user-images.githubusercontent.com/60632552/109564144-a79e4e00-7aae-11eb-9e14-fe9ccfcc8cd1.png)

#### Docker vs. PC
Containers isolate software from their environments to ensure that they will continue to work regardless of differences in development. The Docker runs on a PC so it will use the computer's resources to complete tasks which means they are very lightweight and efficient. Containers are an abstraction at the app layer that packages code and dependencies together.

![image](https://user-images.githubusercontent.com/60632552/109567101-cef71a00-7ab2-11eb-8184-9bdee63405af.png)

Using a Docker is a way to make the application a microservice since it allows the developer to create new additions and updates, and roll them out wuthout disrupting the service. It reduces the amount of time required between development and production.
