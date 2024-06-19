FROM node:22.2.0
#cria diretorio
WORKDIR /app
#copia package e package-lock.json par o diretório corrente
COPY package*.json ./
RUN npm install
#copia todo restante para o diretorio /app
COPY . . 
#inicializa a aplicação
CMD ["node", "server.js"]