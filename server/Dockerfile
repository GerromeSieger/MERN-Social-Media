FROM node:18.13.0-alpine 

WORKDIR /app

COPY . /app

RUN npm install

RUN npm install -g nodemon

EXPOSE 5000

CMD ["npm", "start"]