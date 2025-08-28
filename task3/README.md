# Docker practice
An example of launching simple client-server application with Docker. It builds images with `docker-compose`,
pushes them to `docker registry`, pulls them out of there and launches `containers` based on these iamges.

## Usage
1. ```./build.sh``` to build images
2. ```./push.sh``` to push images to docker registry
3. ```./pull.sh``` to pull images from docker registry
4. ```./launch.sh``` to launch containers
