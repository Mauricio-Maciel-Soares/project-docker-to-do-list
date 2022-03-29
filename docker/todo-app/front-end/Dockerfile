FROM node:14-alpine
WORKDIR /docker/todo-app/front-end
ADD ./node_modules.tar.gz ./
COPY ["/docker/todo-app/front-end", "./"]
EXPOSE 3000
RUN npm start
