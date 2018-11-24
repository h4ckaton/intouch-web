FROM node:10.13.0

WORKDIR /home/node/app

COPY package.json .
RUN npm install --quiet
RUN npm install -g @vue/cli

COPY . .