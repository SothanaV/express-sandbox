FROM node:22-slim

COPY ./package.json /backend/package.json
RUN yarn install

ADD . /backend
WORKDIR /backend