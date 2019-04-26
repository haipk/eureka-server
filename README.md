# eureka-server
eureka-server-docker




# build the docker image
docker build --no-cache=true -t repo/eureka-server .

# run the container
docker run -d repo/eureka-server


# run the docker-compose
docker-compose up -d
