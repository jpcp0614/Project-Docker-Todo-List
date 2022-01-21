FROM mjgargani/puppeteer:trybe1.0 AS todotests

WORKDIR /

EXPOSE 3000

ADD node_modules.tar.gz .

COPY . .

CMD [ "npm", "test" ]

# Obrigado Gabriel Benedicto pela ajuda na resolução do problema!!! \o/