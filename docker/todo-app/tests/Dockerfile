FROM mjgargani/puppeteer:trybe1.0 AS todotests

WORKDIR /app

ADD node_modules.tar.gz /app

COPY . .

CMD [ "npm", "test" ]
