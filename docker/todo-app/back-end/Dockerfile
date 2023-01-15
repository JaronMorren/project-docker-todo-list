FROM node:14
WORKDIR /user/source/app/back-end
EXPOSE 3001
ADD node_modules.tar.gz ./
COPY ./ ./
ENTRYPOINT [ "npm", "start" ]