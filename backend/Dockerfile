FROM node:24-alpine

WORKDIR /home/app

COPY package*.json ./

RUN npm install

COPY . ./

RUN npm run build

EXPOSE 8000

CMD ["sh", "-c", "npm run seed && npm run start"]