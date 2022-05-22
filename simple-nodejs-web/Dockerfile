# specify the base
FROM node:alpine
# install some dependencies
# WORKDIR /usr/app
WORKDIR /usr/app
COPY ./package.json ./
RUN npm install
COPY ./ ./
# default command
CMD [ "npm","start" ]