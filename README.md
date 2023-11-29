# Docker_with_python
Integrating python with docker container. using flask for now, may use django in future.

To build docker image 
docker build --tag python-docker .


To run docker image
docker run -it -p 5000:5000 python-docker
