# We're gonna use a javascript file, so we'll use the node runtime from docker hub
FROM node:20-alpine

WORKDIR /app

# It'll copy everything from out current directory to the docker image 
COPY . .

CMD node hello.js