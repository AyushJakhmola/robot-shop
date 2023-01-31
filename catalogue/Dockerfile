FROM 309017165673.dkr.ecr.us-east-1.amazonaws.com/public:rs-node

ENV INSTANA_AUTO_PROFILE true

EXPOSE 8080

WORKDIR /opt/server

COPY package.json /opt/server/

RUN npm install

COPY server.js /opt/server/

CMD ["node", "server.js"]

