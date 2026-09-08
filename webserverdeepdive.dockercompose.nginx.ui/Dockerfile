# Node runtime stage: source for Node.js binaries (musl build)
ARG NODE_VERSION=24
FROM node:${NODE_VERSION}-alpine AS node-runtime

# Build stage: install deps and bundle the app
FROM node:${NODE_VERSION}-alpine AS build
WORKDIR /app
#COPY package.json . #unable to find this file at path, can be checked later
RUN yarn install
COPY . .
EXPOSE 3000
CMD [ "yarn", "dev" ]