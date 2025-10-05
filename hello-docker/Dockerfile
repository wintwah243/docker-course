FROM node:20-alpine

#this is the directory where commands will be run
WORKDIR /app

#this will copy our current directory to the docker image
#the first dot is our current directory
#the second dot is the path to the current directory within the container
COPY . . 

#command to run the app
CMD node hello.js