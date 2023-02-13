FROM mjgargani/puppeteer:trybe1.0

WORKDIR /tests

COPY package.json .

COPY package-lock.json .

COPY ./ ./

ADD ./node_modules.tar.gz ./

ENTRYPOINT ["npm", "test"]
