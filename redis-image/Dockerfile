# Usee an existing docker image as a base image
FROM alpine


# Download and install a dependency 
RUN apk add --update redis


# Tell the image what to do when it starts
# as a conainer
CMD ["redis-server"]