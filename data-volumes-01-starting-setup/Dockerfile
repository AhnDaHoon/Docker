FROM node

ARG DEFAULT_PORT=80

WORKDIR /app

COPY  package.json /app

RUN npm install

COPY . .

ENV PORT $DEFAULT_PORT

EXPOSE $PORT

CMD [ "node", "server.js" ]