FROM node:21

WORKDIR /teamtalkserver

COPY package.json ./

RUN npm install

COPY . .

EXPOSE 8080

CMD ["npm","run", "start"]
