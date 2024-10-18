FROM node:lts-alpine 

WORKDIR /api

COPY . . 

RUN npm install && npm i -g @nestjs/cli

EXPOSE 3000

CMD npm start
#CMD node server.js 
