FROM mhart/alpine-node:12

WORKDIR /client

COPY package.json ./

RUN npm install

EXPOSE 3000

CMD [ "npm", "start" ]
