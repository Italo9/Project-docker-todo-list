FROM node:14-alpine AS todobackend
ENV FOO=/node_modules.tar.gz
WORKDIR /app
COPY package*.json ./
ADD . $FOO 
RUN npm install
COPY . .
EXPOSE 3001

CMD npm start



