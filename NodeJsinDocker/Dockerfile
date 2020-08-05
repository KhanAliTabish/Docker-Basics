# Specify base image
FROM node:alpine

# Work directory to copy code
WORKDIR /usr/simpleNodeApp

# Copy the code from buid context to container
COPY ./package.json ./   
# Install dependencies
RUN npm install


COPY ./ ./

# Run the node server
CMD ["npm","start"]