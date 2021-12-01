FROM node:14-alpine AS build
WORKDIR /todo-app/back-end/
EXPOSE 3001
ADD ./node_modules.tar.gz ./
COPY . .
CMD ["npm", "start"]
