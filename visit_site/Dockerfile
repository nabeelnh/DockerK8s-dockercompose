# Base image
FROM node:alpine

# Working Directory
WORKDIR /usr/app

# Privisoning with dependencies
COPY ./package.json ./

RUN npm install

COPY ./ ./

# Boot run code
CMD [ "npm", "start" ]