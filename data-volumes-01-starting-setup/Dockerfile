FROM node

WORKDIR /app

COPY package.json .

RUN npm install
#snapshot of images in copy..
COPY . .   

ARG DEFAULT_PORT=80

ENV PORT $DEFAULT_PORT

EXPOSE $PORT

CMD [ "npm", "start" ]