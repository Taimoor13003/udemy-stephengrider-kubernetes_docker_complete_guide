#use an existing docker image as a base
FROM alpine

# Downoad and install the dependency 
RUN apk add --update redis

RUN apk add --update gcc8

#Tell the image what to do when it starts as a container
CMD ["redis-server"]