#Dockerfile Backend
FROM node:16.17.1-alpine

WORKDIR /app

COPY ["package.json", "package-lock.json*", "./"]
RUN npm install 
COPY . .
EXPOSE 5000
CMD ["node", "server.js"]
