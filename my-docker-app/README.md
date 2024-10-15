The following command to build the Docker image
 - docker build -t my-docker-app .

Docker image is built, run a Docker container from the image with this command
 - docker run -p 3000:3000 my-docker-app
   
Navigate : http://localhost:3000.
  We would see "Hello, Docker World!" displayed, confirming that the Dockerized application is running successfully.
