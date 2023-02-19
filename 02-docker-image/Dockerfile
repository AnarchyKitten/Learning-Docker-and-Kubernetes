FROM node:14

WORKDIR /app

COPY package.json /app/

RUN npm install

COPY . /app/

EXPOSE 80

# Not run in building but in excecuting the image.
CMD [ "node", "server.js" ]
