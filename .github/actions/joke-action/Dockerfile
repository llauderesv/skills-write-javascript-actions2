FROM node:18-alpine

WORKDIR /github-action

COPY package*.json .

RUN npm ci

COPY *.js .

RUN ls -al

ENTRYPOINT [ "node", "/github-action/main.js" ]