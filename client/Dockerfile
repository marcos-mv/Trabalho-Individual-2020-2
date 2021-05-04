FROM node:16

RUN yarn global add @quasar/cli

WORKDIR /client

COPY . .

RUN yarn install

RUN yarn global add @quasar/cli

CMD quasar dev 

EXPOSE 8080