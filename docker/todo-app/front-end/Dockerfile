FROM node:14-alpine
EXPOSE 3000
WORKDIR /path
ADD ./node_modules.tar.gz .
COPY . .
CMD [ "npm", "start" ]