FROM node:14

WORKDIR /app

COPY package*.json ./

RUN npm install
RUN npm install @babel/plugin-proposal-private-property-in-object --save-dev

COPY . .

EXPOSE 3000

CMD ["npm", "start"]
