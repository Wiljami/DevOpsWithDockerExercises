FROM node
EXPOSE 5000
COPY package*.json ./
RUN apt-get update && apt-get install -y curl
RUN curl -sL https://deb.nodesource.com/setup_10.x | bash 
RUN apt-get update && apt-get install -y nodejs
RUN node -v
RUN npm -v
RUN npm install -g serve
CMD serve -s -l 5000 dist
