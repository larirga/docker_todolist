FROM node:14-alpine

EXPOSE 3001

WORKDIR /backend

COPY package.json .

COPY package-lock.json .

COPY ./ ./

ADD ./node_modules.tar.gz ./

ENTRYPOINT ["npm", "start"]