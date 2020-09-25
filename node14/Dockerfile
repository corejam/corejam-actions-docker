FROM node:14-alpine

RUN yarn global add lerna && \
    yarn cache clean --mirror && \
    apk add --no-cache perl tar curl bash
