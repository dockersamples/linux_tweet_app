# Linux Tweet App

This is a very simple NGINX website that allows a user to send a tweet. 

It's mostly used as a sample application for Docker 101 workshops. 

## Getting Started

## Pre-requisite

- Install Docker

## Build the Docker Image


```
docker build -t linux_tweet_app .
```

## Running the container

```
docker container run --detach -p 80:80 linux_tweet_app
```

## Accessing the app

Open the browser and access `https://localhost:80`


<img width="1015" alt="image" src="https://github.com/user-attachments/assets/374bcf3d-fcaa-427f-b272-43223026bb0c">

