#use existing docker image as a base
FROM alpine


#download and install dependency
RUN apk add --update gcc
RUN apk add --update redis


#Tell image what to do when start as a container
CMD [ "redis-server" ]

