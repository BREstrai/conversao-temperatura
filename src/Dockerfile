#docker build -t brestrai/conversao-temperatura:v1 .
#docker push brestrai/conversao-temperatura:v1

FROM node:22.6.0
WORKDIR /app
COPY package*.json ./
RUN npm install
COPY . .
EXPOSE 8080
CMD ["node", "server.js"]