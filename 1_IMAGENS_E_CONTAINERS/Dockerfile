FROM node

WORKDIR /1_IMAGENS_E_CONTAINERS/SRC

COPY package*.json .

RUN npm install

COPY . .

EXPOSE 3000

CMD ["node", "app.js"]