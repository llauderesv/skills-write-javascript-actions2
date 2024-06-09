FROM node:18-alpine

COPY package*.json .

RUN npm ci

COPY *.js .

ENTRYPOINT [ "node", "main.js" ]