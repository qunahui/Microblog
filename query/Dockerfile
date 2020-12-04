FROM node:alpine

WORKDIR /app
COPY ./package.json ./
RUN npm install
RUN apk add --update curl
COPY ./ ./

CMD ["npm", "start"]