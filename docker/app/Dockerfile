FROM node:latest

WORKDIR /app

COPY /package.json /app

COPY . /app

USER node

CMD ["/bin/bash", "-c", "yarn install && yarn dev"]