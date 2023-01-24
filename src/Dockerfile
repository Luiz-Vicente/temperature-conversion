# define image
FROM node

#define the work directory
WORKDIR /app

# copy package.json to root from container
COPY package*.json ./

# pre-comandes
RUN npm install

# coping all files to container
COPY . .

# expose a port of my application
EXPOSE 8080

# run this comand when start container
CMD [ "node", "server.js" ]