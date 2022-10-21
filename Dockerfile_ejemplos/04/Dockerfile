FROM node:16

WORKDIR /usr/src/app

COPY package*.json ./
RUN npm install &&  npm ci --omit=dev --only=production

# Copia todo
COPY . .

EXPOSE 8080
CMD [ "node", "server.js" ]
