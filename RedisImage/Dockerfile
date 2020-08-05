# Use an existing image as a Base image
FROM alpine

# Download and install a dependency
RUN apk add --update redis

# Tell image what to do when it starts as a container
CMD [ "redis-server" ]