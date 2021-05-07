FROM node:15

WORKDIR /usr/src/app

RUN npm install mysql --save
COPY index.js .

CMD [ "node", "index.js" ]