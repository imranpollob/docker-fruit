FROM node:12-alpine

WORKDIR /usr/src/app

COPY package*.json ./
RUN npm install
RUN npm install nodemon -g

CMD ["nodemon", "server.js"]