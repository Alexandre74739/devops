FROM node:24-alpine

WORKDIR /app

COPY package.json ./

RUN npm install

COPY . .

RUN npm run build

# On remplace par 40213 pour le compose.yaml 
EXPOSE 4173

CMD ["npm", "run", "preview"]