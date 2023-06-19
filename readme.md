# How to push your local dockerize project into docker hub and use it.
### Build and login
- docker-compose build
- docker login
### If you have multiple image then you should run the below command for each user
- docker tag image1:latest your-dockerhub-username/image1:latest
- docker push your-dockerhub-username/your-image-name[:TAG]

### Use the image from the docker hub
Please checkeout the `docker-compose.yml` to explore how to  use the docker image in the project
Now you just deploy `docker-compose.yml` into the client server with necessiate env file if needed.
Then run the compose file in the server.



