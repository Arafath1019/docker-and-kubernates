# Specify a base image
FROM node:alpine

# working directory
WORKDIR /usr/app

# Install some dependencies
COPY ./package.json ./
RUN npm install
RUN ./ ./

# Default command
CMD ["npm", "start"]
