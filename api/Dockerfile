FROM node:24

WORKDIR /app

COPY package*.json ./

RUN npm install

COPY . .

# On remplace par 40223 pour le compose.yaml 
EXPOSE 1994

CMD ["npm", "run", "dev"]