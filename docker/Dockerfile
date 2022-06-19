FROM node:7.7.2-alpine
WORKDIR /usr/app
COPY package.json .
RUN npm install
RUN npm run init
RUN npm run start

COPY . .
