FROM node:12-alpine

WORKDIR /usr/src/app

COPY ../../hotelszone_node_partner/package*.json ./

RUN npm install 

COPY ../../hotelszone_node_partner/ .

EXPOSE 8080

CMD ["npm", "start"]

