FROM node:10-alpine

COPY package*.json ./

RUN npm install
COPY . .

ENV FRONT_URL http://localhost:5000

EXPOSE 8000

CMD ["npm", "start"]
