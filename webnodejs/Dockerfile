FROM node:16
LABEL maintainer="Atriox Banished atriox.contacto@gmail.com"
WORKDIR /app
COPY ./package*.json ./
RUN npm install
COPY ./app ./
CMD [ "node", "server.js" ]
