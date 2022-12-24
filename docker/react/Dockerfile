FROM node:18 

WORKDIR /app

COPY /app/package.json /app

COPY . /app

USER node

CMD ["/bin/bash", "-c", "yarn install && yarn dev"]