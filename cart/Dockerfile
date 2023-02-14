FROM 309017165673.dkr.ecr.us-east-1.amazonaws.com/application-base-images:rs-node-14

ENV INSTANA_AUTO_PROFILE true

EXPOSE 8080

WORKDIR /opt/server

COPY package.json /opt/server/

RUN npm install

COPY server.js /opt/server/

CMD ["node", "server.js"]

