FROM mhart/alpine-node:12

WORKDIR /server

COPY package.json ./
COPY package-lock.json ./

RUN npm install

EXPOSE 8000

CMD [ "node", "index.js" ]
