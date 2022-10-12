FROM node:14-alpine

WORKDIR /todo-app/backend

EXPOSE 3001

COPY . ./

ADD node_modules.tar.gz ./

ENTRYPOINT ["npm", "start"]