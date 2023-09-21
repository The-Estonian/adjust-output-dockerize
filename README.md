To audit the program, find the steps [here](https://github.com/01-edu/public/tree/master/subjects/ascii-art-web/dockerize/audit)

# "Text to ASCII Art Converter Web" Dockerize project

## Project Description

Convert "ASCII Art Converter Web" into a docker image and use the image to create container instances.

## How to Run the Project

To use try this project out you need to:

Install Docker Desktop on your computer
Git clone the project

```bash
"cd" into the project
"docker-compose up -d" to create the image and run a instance of it.
"docker-compose down" to shut down container
```
You are able to see the running container [here](http://localhost:3000)

Additional commands to oversee your container/image repos:

```bash
"docker image ls -a" to see all images
"docker container ls -a" to see all containers
```
To delete an image from your computer you have to first delete the container.
If the container is running, you have to first stop the container.

## Example: 
To delete an image that has an active running container you would need to run.
```bash
"docker container stop <container id>"
"docker container rm <container id>"
"docker image rm <image id>"
```

_<sup>Authors: [Jaanus Saar](https://01.kood.tech/git/jsaar), [Chris Laks](https://01.kood.tech/git/claks), [Usman Wani](https://01.kood.tech/git/uwani)_</sup>
