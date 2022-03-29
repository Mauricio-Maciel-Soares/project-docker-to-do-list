FROM node:14-alpine AS todobackend
WORKDIR /back-end
ADD ./node_modules.tar.gz ./
COPY ["/todo-app/back-end", "./"]
RUN npm start
RUN npm run build
EXPOSE 3001
