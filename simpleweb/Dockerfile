# Specify a base image.
FROM node:alpine

#Specify a Working Directory
WORKDIR /usr/app

# Install some dependencies
COPY ./package.json ./
RUN npm install
COPY ./ ./


# Default command
CMD [ "npm", "start" ]
