# Document title

**Prerequisite knowledge**: web, server, infrastructure, virtualization, bash

## Intro
Docker is used to run software packages called "containers".
Containers are isolated from each other and bundle their own application, tools, libraries and configuration files;
they can communicate with each other through well-defined channels.
All containers are run by a single operating system kernel and are thus more lightweight than virtual machines.
Containers are created from "images" that specify their precise contents.
Images are often created by combining and modifying standard images downloaded from public repositories.
[[Source](https://en.wikipedia.org/wiki/Docker_(software\))]

## Classification / acceptance questions

### Apprentice aka _I have a container running_
* I can setup Docker on my system
* I can run an image from a public repository

### Intermediate aka _I have my app running in a container_
* I know what a Docker image and container are
* I can define a container with Dockerfile, use it to build the image and run it
* I can map a container port to a different external port
* I can publish an image to a repository

### Advanced aka _I have my complex app running in multiple containers_
* I can use docker-compose file to define multi-layered services
* I know when to use Docker Stack and when Docker Compose
* I know how to manage application data using volumes and bind mounts
* I know how to use multistage builds to keep images lean
* I know how to set up a Swarm cluster and run an app in it

### Master aka _?_
* I know how to set up live debug for an app running inside a container
* I know how to take advantage of Docker security features
* I understand how an ingress routing mesh works
* I know how to set up a private registry

## Sources
* [Docker docs](https://docs.docker.com/get-started/)
* [The Difference Between Docker Compose And Docker Stack](https://vsupalov.com/difference-docker-compose-and-docker-stack/)
* [Developer Tools Tutorials](https://github.com/docker/labs/blob/master/developer-tools/README.md)
* [Docker Security](https://github.com/docker/labs/blob/master/security/README.md)

## All custom stuff
**Next steps**: monitoring, deployment, continuous integration, continuous deployment, kubernetes
