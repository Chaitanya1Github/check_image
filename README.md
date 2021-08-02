# difference-between-Dockerfile-and-docker-compose.

1. Dockerfile is resposible for creating images
2. docker-compose.yml also also create images. Moreover it creates multiple images/containers.
3. Dockerfile can create only one image. docker-compose.yml can create one or more images.
4. docker-compose triggers Dockerfile and then Dockerfile creates image accordingly.
5. if the code resides on github along with Dockerfile then you can build image outof that Dockerfile. Let`s see how to do that:
    a) open power shell
    b) command syntax: docker build github_url
    c) command example: docker build 
