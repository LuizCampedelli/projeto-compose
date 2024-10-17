FROM node:14

WORKDIR /backend

COPY package*.json ./

RUN npm install
RUN npm install cors
COPY . .

EXPOSE 3000

CMD [ "node", "app.mjs" ]
