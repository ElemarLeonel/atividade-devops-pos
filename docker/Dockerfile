FROM node:16

# criando dir 
WORKDIR /usr/src/app

# instala depedencias
COPY package*.json ./

RUN npm install

COPY . .

EXPOSE 8080
CMD [ "node", "server.js" ]
