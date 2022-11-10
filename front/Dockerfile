FROM node:slim

WORKDIR /usr/src/app

COPY . .
# .env have to be specified explicitely because docker will ignore . files otherwise
# COPY .env .env

RUN npm i --silent

CMD ["npm", "run", "dev"]