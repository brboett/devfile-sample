FROM node:current-slim

WORKDIR /usr/src/app
COPY . .
RUN npm install

RUN mkdir /opt/bryan

EXPOSE 3001
CMD [ "npm", "run", "console" ]
