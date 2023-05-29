# build stage
FROM node:16-alpine
WORKDIR /app
COPY . .
RUN yarn ci
CMD ["yarn", "start"]
