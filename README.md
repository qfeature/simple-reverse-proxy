# Overview
This is a very simple, bare-bones nginx reverse proxy project created to use with simple-express project.

# Local Setup
* Install dependencies: there is none.
* Run server: need to run the docker image instead.

# Usage
By default, the application should be loaded on `localhost:8080`. It should provide an HTTP 200 response when loaded at `localhost:8080/api/health`.

# Container Setup
* Build image: `docker build .`
* Run container with image: `docker run {image_id}` where `image_id` can be retrieved by running `docker images` and found under the column `IMAGE ID`

# Container teardown
* Remove container: `docker kill {container_id}` where `container_id` can be retrieved by running `docker ps` and found under the column `CONTAINER ID`
