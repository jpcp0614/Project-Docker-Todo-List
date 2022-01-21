FROM node:14-alpine AS build

WORKDIR /app.frontend

ADD node_modules.tar.gz .

COPY . .

EXPOSE 3000

ENTRYPOINT ["npm", "start"]
