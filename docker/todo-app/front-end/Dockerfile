FROM node:14-alpine AS build
WORKDIR /todo-app/front-end/
EXPOSE 3000
ADD ./node_modules.tar.gz ./
COPY . .
ENV REACT_APP_API_HOST=todobackend \
    REACT_APP_API_PORT=3001
CMD ["npm", "start"]