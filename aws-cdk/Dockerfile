FROM node:14-alpine

RUN apk add --update py-pip && \
    pip install awscli        

RUN yarn global add aws-cdk && \
    yarn cache clean --mirror && \
    apk add --no-cache perl tar curl bash