FROM node:15

WORKDIR /usr/src/app

COPY ./package*.json /usr/src/app/

RUN npm install

EXPOSE 3000

CMD ["npm", "run", "dev"]