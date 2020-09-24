FROM node:14-alpine

RUN yarn global add lerna vercel json && \
    yarn cache clean --mirror && \
    apk add --no-cache perl tar curl bash
