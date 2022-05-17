FROM node:14-alpine AS todofrontend

WORKDIR /todo-app/front-end

ADD node_modules.tar.gz ./

COPY . . 

EXPOSE 3000

ENTRYPOINT [ "npm", "start" ]
