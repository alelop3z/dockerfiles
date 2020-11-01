FROM node:14.15-alpine

COPY . /www/app

RUN npm install -g @ionic/cli

WORKDIR /www/app
RUN npm install

EXPOSE 8100 35729 

CMD bash -c "ionic serve --host=0.0.0.0 --port=8100 --poll 1"