FROM node:14-alpine

WORKDIR /todo-app/front-end

COPY package.json .

RUN npm install

COPY . . 

ADD node_modules.tar.gz ./todo-app/front-end

EXPOSE 3000

ENTRYPOINT [ "npm", "start" ]
