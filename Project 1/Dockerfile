# Simple Dockerfile for the conversao-temperatura project that can be found here: https://github.com/KubeDev/conversao-temperatura
FROM node
WORKDIR /app
# This will copy all the package files:
COPY package*.json ./ 
RUN npm install
# This will copy all the other files into the container:
COPY . . # Important to do it after the RUN or the container will use the RUN command after every update!
EXPOSE 8080
CMD ["node", "server.js"]
