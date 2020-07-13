FROM node:12.18.1-alpine

WORKDIR /usr/app

COPY package*.json ./

RUN npm install

COPY . .

EXPOSE 4000 

CMD ["npm", "run", "dev"]

#Os comandos EXPOSE e CMD não são necessários pois já foram adicionados no arquivo docker-compose.yml
#Está explícito aqui somente a título de aprendizado.