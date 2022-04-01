FROM node
WORKDIR  /app
#primeiro copiar o packer, depois o resto. boa pratica
COPY package*.json ./
RUN npm install
COPY . . 
EXPOSE 8080
CMD ["node","server.js"] 