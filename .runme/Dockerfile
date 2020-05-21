FROM node:12.16.2
WORKDIR /dist
COPY . .
RUN "yarn install && yarn build"
ENTRYPOINT yarn build
