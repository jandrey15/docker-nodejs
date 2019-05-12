# Example app node.js with Docker

## Build image
`docker build -t your_dockerhub_username/nodejs-image-demo .`

## Check your images
`docker images`

## Build the container
`docker run --name nodejs-image-demo -p 80:8080 -d your_dockerhub_username/nodejs-image-demo`

## running containers
`docker ps`

## Stop container
`docker stop id-container`

## List your all of your images
`docker images -a`

## Remove the stopped container and all of the images
`docker system prune -a`
