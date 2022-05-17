FROM mjgargani/puppeteer:trybe1.0

WORKDIR /todo-app/tests/

COPY package.json .

RUN npm install

COPY . . 

ADD node_modules.tar.gz ./todo-app/tests/

EXPOSE 3000

ENTRYPOINT [ "npm", "test" ]
