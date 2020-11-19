# polynote-meapy-docker

Docker image based on https://github.com/polynote/polynote/tree/master/docker which includes [Meapy](https://pypi.org/project/meapy/)

## Getting Started
Build the Dockerfile and start the docker-compose stack in order to use the prepared meapy notebook.

```
> docker build -t polynote-meapy-docker:latest .

> docker-compose up
```

Connect to `localhost:8192` where you can find the polynote examples and the meapy notebook