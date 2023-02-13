FROM node:14-alpine

EXPOSE 3001

WORKDIR /backend

COPY . .

ADD ./node_modules.tar.gz ./

CMD ["npm" "start"]