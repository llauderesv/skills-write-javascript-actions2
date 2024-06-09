FROM node:18-alpine

WORKDIR /github/workspace

COPY package*.json .

RUN npm ci

COPY *.js .

RUN ls -al

ENTRYPOINT [ "node", "main.js" ]