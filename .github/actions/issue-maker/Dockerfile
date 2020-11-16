FROM node:slim

COPY package*.json ./

RUN npm install; npm install -g npm@7.0.11; npm install

COPY . .

CMD [ "node", "/src/index.js" ]
