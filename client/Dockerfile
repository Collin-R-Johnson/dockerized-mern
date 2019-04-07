#alpine is a lightweight version of node on alpine linux
FROM mhart/alpine-node:10.15.3

WORKDIR /client

COPY package*.json /client/

RUN npm install

COPY . /client/

EXPOSE 3000

CMD ["npm", "start"]