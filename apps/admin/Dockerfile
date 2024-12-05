FROM node:18-alpine

WORKDIR /app

COPY package*.json ./
RUN yarn install

COPY . .

RUN yarn build:adimn

CMD ["yarn", "start:admin"]
