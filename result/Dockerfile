FROM node:21-alpine

#repertoire dans le container
WORKDIR /app

COPY package.json .

#installe les dependances
RUN npm install --production

# copie tous le code
COPY . .

# sur le port 80
EXPOSE 80

CMD ["node", "server.js"]