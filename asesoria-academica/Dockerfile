FROM node:16

WORKDIR /usr/src/app

COPY asesoria-academica/package*.json ./

RUN npm install

COPY asesoria-academica .

EXPOSE 4001

CMD [ "node", "server.js" ]