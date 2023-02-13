FROM node:14-alpine

EXPOSE 3000

WORKDIR /frontend

COPY package.json .

COPY package-lock.json .

COPY . .

ADD ./node_modules.tar.gz ./

CMD ["npm" "start"]
