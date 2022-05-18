FROM node:14-alpine AS todofrontend
ENV FOO=/node_modules.tar.gz
WORKDIR /app
COPY package*.json ./
ADD . $FOO 
RUN npm install
COPY . .
EXPOSE 3000

CMD npm start



