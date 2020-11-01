FROM node:14.15-alpine

WORKDIR /www/app
COPY package*.json ./
RUN npm install -g @vue/cli @vue/cli-service-global
RUN npm install
COPY . .
CMD ["npm", "run", "serve"]