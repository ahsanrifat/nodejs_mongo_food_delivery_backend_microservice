FROM node:19.7

WORKDIR /app

COPY package*.json ./

RUN npm install

RUN npm i nodemon

COPY . .

EXPOSE 300

CMD ["npm","start"]


