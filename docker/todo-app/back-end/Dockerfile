FROM node:14-alpine

WORKDIR /todo-app/back-end

COPY package.json .

RUN npm install

COPY . . 

ADD node_modules.tar.gz ./todo-app/back-end

EXPOSE 3001

ENTRYPOINT [ "npm", "start" ] 
