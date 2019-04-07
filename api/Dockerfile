#alpine is a lightweight version of node on alpine linux
FROM mhart/alpine-node:10.15.3

WORKDIR /api

COPY package*.json /api/

RUN npm install

COPY . /api/

#exposes port 80 of container
EXPOSE 80

CMD ["npm", "start"]