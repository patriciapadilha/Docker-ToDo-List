FROM node:14-alpine

WORKDIR /back-end

COPY package*.json /back-end

ADD node_modules.tar.gz .

RUN npm install

COPY . .

EXPOSE 3001


