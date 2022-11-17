FROM node:16

WORKDIR /usr/src/app

COPY asesoria-academica-micro/package*.json ./

RUN npm install

COPY asesoria-academica-micro .

EXPOSE 4000

CMD [ "node", "server.js" ]