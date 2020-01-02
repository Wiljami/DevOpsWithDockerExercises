FROM node:10-alpine

COPY package*.json ./
RUN npm install

COPY . .
RUN npm run build

CMD ["npx", "serve", "-s", "-l", "5000", "dist"]
EXPOSE 5000
