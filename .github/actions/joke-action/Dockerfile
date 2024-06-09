FROM node:18-alpine

COPY package*.json .

RUN npm ci

COPY *.js .

RUN ls -al

ENTRYPOINT [ "node", "main.js" ]