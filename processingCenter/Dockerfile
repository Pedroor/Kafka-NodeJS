FROM node:12.18.1

WORKDIR /usr/app

COPY package.json .
RUN npm install

COPY . .

EXPOSE 3001

CMD ["npm", "start"]