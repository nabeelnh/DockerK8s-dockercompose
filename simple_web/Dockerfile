# Base image
FROM node:alpine

# Provide a working directory
# All following commands will be executed relative to this working directory
WORKDIR /usr/app

# Provisioning commands / install dependencies
COPY ./package.json ./

RUN npm install

COPY ./ ./

# Command to run at the start of a container made from this image
# / default command
CMD ["npm", "start"]