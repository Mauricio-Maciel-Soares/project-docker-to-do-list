FROM node:14-alpine
WORKDIR /docker/todo-app/back-end
ADD ./node_modules.tar.gz ./
COPY ["/docker/todo-app/back-end", "./"]
EXPOSE 3001
RUN npm start
