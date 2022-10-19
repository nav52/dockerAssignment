# Assignment2-Docker

## Task1

Demonstrate a minimum of 15 basic docker commands with an explanation and screenshots.

**Solution:**

1. **docker pull** **<<image_name>>** —> Pulls the image from the repository

![Untitled](Assignment2-Docker/Untitled.png)

 

1. **docker —version** —> Displays the version of the docker

![Untitled](Assignment2-Docker/Untitled%201.png)

1. **docker run** —> Runs the image as a container

Example: 

docker run -d -p 80:80 docker/getting-started

-d —> detach mode 

-p 80:80 —> maps the host port 80 to container port 80

![Untitled](Assignment2-Docker/Untitled%202.png)

1. **docker images** —> Displays the current pulled images

![Untitled](Assignment2-Docker/Untitled%203.png)

1. **docker ps** —> To list all the running containers.

![Untitled](Assignment2-Docker/Untitled%204.png)

1. **docker stop <<container_id>>** —> Stops the running container

![Untitled](Assignment2-Docker/Untitled%205.png)

1. **docker start <<container_id>>** —> Starts the container

![Untitled](Assignment2-Docker/Untitled%206.png)

1. **docker logs <<container_id>>** —> Displays logs of the container
    
    ![Untitled](Assignment2-Docker/Untitled%207.png)
    
2. **docker kill <<container_id>>** —> Force shutdown the container
    
    ![Untitled](Assignment2-Docker/Untitled%208.png)
    

10. **docker rm <<container_id>>** —> Removes the container from the machine

![Untitled](Assignment2-Docker/Untitled%209.png)

1. **docker rmi <<image_name>>** —> Removes the image from the machine
    
    ![Untitled](Assignment2-Docker/Untitled%2010.png)
    
2.  **docker rename <<old_name>> <<new_name>>**  —> Rename the container
    
    ![Untitled](Assignment2-Docker/Untitled%2011.png)
    
3. **docker port <<container_id>>** —> Displays the port mapping of the container
    
    ![Untitled](Assignment2-Docker/Untitled%2012.png)
    
4. **docker stats** —> Displays the usage statistics of docker
    
    ![Untitled](Assignment2-Docker/Untitled%2013.png)
    
5. **docker inspect <<image_name>>** —> Get the low-level information on the image in JSON format
    
    ![Untitled](Assignment2-Docker/Untitled%2014.png)
    
6. **docker build -t <<image_name>> .** —> To build images
    
    ![Untitled](Assignment2-Docker/Untitled%2015.png)
    

## Task2

[Hello, World Docker Image](https://hub.docker.com/_/hello-world) Run Hello World Docker Image Locally.

**Solution:**

![Untitled](Assignment2-Docker/Untitled%2016.png)

## Task3

Create a hello world FastAPI application. Create a Dockerfile for your FastAPI hello world application. Build Docker image using Docker file. Run the docker image build in the previous step. Push your Docker image to Docker Hub.

**Solution:**

[https://github.com/nav52/dockerAssignment](https://github.com/nav52/dockerAssignment)

![Untitled](Assignment2-Docker/Untitled%2017.png)

![Untitled](Assignment2-Docker/Untitled%2018.png)

![Untitled](Assignment2-Docker/Untitled%2019.png)

## Task4

Automate the Assignment below task using GitHub action.

1. Build Docker Image
2. Push Docker Image to Docker hub.

**Solution:**

[https://github.com/nav52/dockerAssignment](https://github.com/nav52/dockerAssignment)

- Create Docker hub token and add them to GitHub repository secrets
- Create the YAML file in the .github/workflows/ to login to Docker hub, build the image on push to the main branch and push the ‘image’ to the docker hub repository.

![Untitled](Assignment2-Docker/Untitled%2020.png)