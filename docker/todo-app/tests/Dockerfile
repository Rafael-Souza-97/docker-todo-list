FROM node:14-alpine

WORKDIR /todo-app/tests

COPY package*.json ./

RUN npm install

COPY . ./todo-app/tests/

ADD node_modules.tar.gz ./todo-app/tests

ENTRYPOINT [ "npm", "test" ]
