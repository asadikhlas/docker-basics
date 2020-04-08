#Use an existing docker image as a base
FROM alpine

#download and install dependancy
RUN apk add --update redis

#tell the image what to do when it start as a container
CMD [ "redis-server" ]