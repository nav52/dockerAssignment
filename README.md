# dockerAssignment
Assignment task solutions can be found [here](https://github.com/nav52/dockerAssignment/docs/Assignment2-Docker.pdf)
## FastAPI hello world application.

### Running instructions
1. To pull the latest image from the docker hub
```
docker pull naveenkaranth/hello-fastapi
```
2. To run the image in a container,
```
docker run -d -p 8080:80 naveenkaranth/hello-fastapi
```

__NOTE__: Container port is 80

