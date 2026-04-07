#Builder
FROM node:18-alpine as builder

WORKDIR /app
COPY package*.json ./
RUN npm install --only=production
COPY server.js .

CMD ["npm", "start"]
