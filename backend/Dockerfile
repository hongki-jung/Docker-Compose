FROM node:alpine

WORKDIR /app

COPY ./pckage.json ./

RUN npm install

COPY . .

CMD ["npm", "run", "start"]