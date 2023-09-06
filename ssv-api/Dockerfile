FROM node:14-alpine

WORKDIR /ssv-api
COPY package.json .
RUN npm install
COPY . .
CMD npm start
