FROM node:20.14-alpine3.20

WORKDIR /app
COPY . .

# COPY package*.json ./
RUN npm install

EXPOSE 3001

CMD ["node", "server.js"]