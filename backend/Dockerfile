FROM node:16.2.0-alpine

# Create app directory
WORKDIR /usr/src/app

COPY package*.json ./

RUN yarn

COPY . .

EXPOSE 8080

CMD [ "yarn", "start" ]