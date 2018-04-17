FROM node:8.9.4
RUN mkdir -p /usr/src/app/server-mongodb
WORKDIR /usr/src/app/server-mongodb
COPY package*.json /usr/src/app/server-mongodb/
RUN npm install -g nodemon && npm install

EXPOSE 3001
CMD [ "npm", "start" ]