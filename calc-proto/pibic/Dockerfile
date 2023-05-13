FROM node:alpine

RUN mkdir /app

WORKDIR /app

COPY package.json /app

COPY . /app

CMD ["npm", "run", "start"]