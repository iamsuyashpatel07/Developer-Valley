FROM node:17-alpine

RUN yarn add -g nodemon

WORKDIR /app

COPY package.json .

RUN yarn

COPY . .

EXPOSE 4000

CMD ["yarn", "run","dev"]