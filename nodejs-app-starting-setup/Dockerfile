FROM node

WORKDIR /app 

COPY package.json /app

RUN npm install 
# copy . (what's in) to /app file or . 
COPY . /app
#Expose certain port, convention not necessary
EXPOSE 80 
#run when the container is started based on the image created
CMD ["node", "server.js"] 

#layer based architecture 