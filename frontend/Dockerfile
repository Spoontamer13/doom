FROM node:alpine

WORKDIR /the/workdir/time-app

COPY package*.json ./

RUN npm install

COPY . .

EXPOSE 8954

CMD ["npm", "run", "dev"]