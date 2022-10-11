FROM node:14-alpine

WORKDIR /todo-app/tests

COPY package*.json ./

COPY . ./todo-app/tests/

ADD node_modules.tar.gz ./todo-app/tests

ENTRYPOINT [ "npm", "test" ]
