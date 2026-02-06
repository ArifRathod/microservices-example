FROM node:25.6.0-bookworm

COPY . /src

WORKDIR /src

RUN npm install --production

EXPOSE 3000

CMD npm start