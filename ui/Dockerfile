FROM node:16-alpine as build-stage

WORKDIR /ui

COPY . .

RUN npm install

CMD ["npm", "run", "dev"]
