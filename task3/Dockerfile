FROM node:16-alpine

WORKDIR /home/ilovedocker/app

COPY package*.json ./

RUN npm i --omit=dev

COPY . .

EXPOSE 3032
CMD [ "node", "main.js" ] 
