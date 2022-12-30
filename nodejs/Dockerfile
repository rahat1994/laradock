ARG LARADOCK_NODE_VERSION=latest
FROM node:${LARADOCK_NODE_VERSION}-alpine

LABEL maintainer="Huadong Zuo <admin@zuohuadong.cn>"

RUN apk --no-cache add tzdata ca-certificates && npm install pm2@latest -g 

WORKDIR /var/www/hotelszone_node_partner

EXPOSE 3000-3010

CMD ["pm2-runtime", "node","hello.js"]
