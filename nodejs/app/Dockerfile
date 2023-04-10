FROM node:alpine

RUN mkdir /app
ADD ./app /app
WORKDIR /app
RUN npm install --silent

CMD npm start
