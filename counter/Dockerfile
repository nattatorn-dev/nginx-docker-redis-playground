#FROM node:boron
FROM node:slim

# Create app directory
RUN mkdir -p /usr/src/app
WORKDIR /usr/src/app

# Install app dependencies
COPY . /usr/src/app
RUN npm i

# Bundle app source



EXPOSE 8080 
CMD [ "npm", "start" ]


