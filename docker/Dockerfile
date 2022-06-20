FROM node:lts-alpine3.15
WORKDIR /usr/app
COPY package.json .
RUN npm install
RUN npm run init
RUN npm run start

COPY . .
