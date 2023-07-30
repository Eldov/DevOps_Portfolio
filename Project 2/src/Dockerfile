# Simple Dockerfile for the kube-news project that can be found here: https://github.com/KubeDev/kube-news
FROM node:18.11.0
WORKDIR /app
COPY package*.json ./
RUN npm install
COPY . .
EXPOSE 8080
CMD ["node", "server.js"]
