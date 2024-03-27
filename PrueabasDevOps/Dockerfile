# Dockerfile para el Backend (Node.js) y MongoDB
# Dockerfile.backend

FROM node:14

WORKDIR /app

COPY package*.json ./

RUN npm install

COPY . .

EXPOSE 3000

CMD ["npm", "start"]
