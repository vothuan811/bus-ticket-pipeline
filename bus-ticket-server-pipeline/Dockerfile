FROM node:16-alpine

WORKDIR /app

COPY . .

RUN apk add bash

RUN npm install -g pm2

RUN yarn bootstrap

RUN npm install mongoose-paginate-v2

CMD pm2-runtime start "yarn start" --name bus-server
