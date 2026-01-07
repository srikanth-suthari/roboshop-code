FROM node:20
WORKDIR /opt/server
COPY package.json .
COPY *.js .
EXPOSE 8080
RUN adduser roboshop
USER roboshop
CMD ["node", "server.js"]
