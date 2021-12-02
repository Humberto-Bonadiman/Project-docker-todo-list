FROM mjgargani/puppeteer:trybe1.0 AS build
WORKDIR /todo-app/tests/
ADD ./node_modules.tar.gz ./
COPY . .
ENV FRONT_HOST=todofrontend \
    FRONT_PORT=3000
CMD ["npm", "start"]