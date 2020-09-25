FROM cypress/browsers:node14.7.0-chrome84

RUN yarn global add vercel cypress && \
    cypress install && cypress verify && cypress info && \
    yarn cache clean --mirror && \
    apt-get install -y tar wget && \
    apt-get clean && \
    rm -rf /var/lib/apt/lists/* 
