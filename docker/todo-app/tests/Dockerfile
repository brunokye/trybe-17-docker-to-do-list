FROM mjgargani/puppeteer:trybe1.0
WORKDIR /path
ADD ./node_modules.tar.gz .
COPY . .
CMD [ "npm", "test" ]