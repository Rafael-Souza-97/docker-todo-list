FROM node:14-alpine

WORKDIR /todo-app/frontend

COPY package*.json ./

EXPOSE 3000

COPY src ./todo-app/frontend/src

ADD node_modules.tar.gz ./todo-app/frontend

ENTRYPOINT [ "npm", "start" ]
