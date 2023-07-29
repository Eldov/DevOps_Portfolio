# Simple Dockerfile for the conversao-temperatura project that can be found here: https://github.com/KubeDev/conversao-temperatura
FROM node
WORKDIR /app
COPY package*.json ./
RUN npm install
COPY . .
EXPOSE 8080
CMD ["node", "server.js"]
