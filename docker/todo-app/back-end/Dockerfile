FROM node:14-alpine
WORKDIR /back-end
ADD ./node_modules.tar.gz ./
COPY ["/todo-app/back-end", "./"]
RUN npm start && npm run build
EXPOSE 3001
