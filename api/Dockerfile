FROM node:16.4-alpine

WORKDIR /usr/api
COPY package.json ./
COPY package-lock.json ./
COPY ./src/db/ ./src/db/
COPY . .
RUN npm install --quiet
