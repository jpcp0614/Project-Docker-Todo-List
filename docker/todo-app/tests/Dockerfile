FROM mjgargani/puppeteer:trybe1.0 AS build

WORKDIR /app/tests

ADD node_modules.tar.gz .

COPY . .

ENTRYPOINT [ "npm", "start" ]
