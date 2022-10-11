FROM node:14-alpine

WORKDIR /todo-app/backend

COPY package*.json ./

EXPOSE 3001

RUN npm install

COPY src ./todo-app/backend/src

ADD node_modules.tar.gz ./todo-app/backend

ENTRYPOINT [ "npm", "start" ]
