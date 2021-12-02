FROM mjgargani/puppeteer:trybe1.0 AS build
WORKDIR /todo-app/tests/
EXPOSE 3000
ADD ./node_modules.tar.gz ./
COPY . .
CMD ["npm", "test"]