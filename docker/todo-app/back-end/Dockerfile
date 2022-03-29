FROM node:14-alpine
WORKDIR /back-end
ADD ./node_modules.tar.gz ./
COPY ["/todo-app/back-end", "./"]
RUN npm start
EXPOSE 3001
