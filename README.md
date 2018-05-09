# ubuntusugar7
The purpose of this repository to help web developers to setup specific environment with following 
  * PHP 5.6 
  * mysql 
  * elastic search.
## Some Docker Commands :

### List all containers (only IDs)
docker ps -aq

### Stop all running containers
docker stop $(docker ps -aq)

### Remove all containers
docker rm $(docker ps -aq)

## Remove all images
docker rmi $(docker images -q)
