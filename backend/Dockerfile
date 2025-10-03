FROM node:18

WORKDIR /app

COPY package*.json ./

COPY server.js ./

RUN npm ci

COPY . .

EXPOSE 3001

CMD ["node", "server.js"]