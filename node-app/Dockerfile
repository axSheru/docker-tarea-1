FROM node

WORKDIR /app

COPY package.json /app

#RUN se ejecuta cuando una imagen es creada.
RUN npm install

COPY . /app

#Esto es recomendado, realmente el puerto se expone al correr el contenedor con docker run -p
EXPOSE 80

#CMD se ejecuta cuando un contenedor es creado.
CMD ["node", "server.js"]