FROM node:14-alpine AS build
WORKDIR /docker/todo-app/front-end/
EXPOSE 3000
ADD node_modules.tar.gz .
COPY . .
ENTRYPOINT [“npm start;”]