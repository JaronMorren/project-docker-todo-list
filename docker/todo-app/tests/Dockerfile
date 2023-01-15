FROM mjgargani/puppeteer:trybe1.0
WORKDIR /user/source/app/tests
ADD node_modules.tar.gz ./
COPY ./ ./
ENTRYPOINT [ "npm", "test" ]