FROM mjgargani/puppeteer:trybe1.0
ADD ./node_modules.tar.gz /usr/src/app/
COPY ./* /usr/src/app/
ENTRYPOINT [ "npm", "test" ]
