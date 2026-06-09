FROM node:20

WORKDIR /app

COPY package*.json ./

RUN npm install && npm rebuild

COPY . .

EXPOSE 5000

CMD ["node", "server.js"]
