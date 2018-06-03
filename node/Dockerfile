FROM node:9.11.1-alpine

RUN mkdir /src

WORKDIR /src
ADD app/package.json /src/package.json
RUN npm install

EXPOSE 3000

CMD node app/bin/www