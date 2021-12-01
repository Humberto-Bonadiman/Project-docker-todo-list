FROM node:14-alpine AS build
WORKDIR /
EXPOSE 3001
ADD node_modules.tar.gz ./
COPY . .
CMD [“npm”, “start”]
