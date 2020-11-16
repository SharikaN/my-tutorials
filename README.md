# my-tutorials

This is a tutorila repository on How to Create a go based Web App and build a Docker Image of it.

Use the following commands 

## Build GO app

    go build helloWorldOS.go

## Create docker image

    docker build -t my-go-app .

## Run docker container with GO app 

    docker run -p 8888:8888 -it my-go-app


    You should be able to see "Hello, Welcome to GO Tutorial!" @ http://localhost:8888/
