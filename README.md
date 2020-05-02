# docker-files

This repo hold some of my docker files, that I am using as a portable development environment. 


To use this repo have docker installed.

Build the docker images `docker build -f Dockerfiles/base.yaml .`
Tag the new image `docker tag <image_id> repo/path/name:version` 
Start the container `docker-compose -f .\compose-files\dev-compose.yaml`