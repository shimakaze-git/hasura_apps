FROM node:10-buster

WORKDIR /opt/workspace

ENV USE_LOCAL_BACKEND 1

RUN apt-get update -y

CMD pwd && ls -la

# RUN apt-get install -y curl openjdk-11-jre-headless

# RUN curl -sL https://deb.nodesource.com/setup_10.x | bash - \
#     && apt-get install -y nodejs

# RUN npm install -g firebase-tools && mkdir functions

# COPY ./package.json ./
# COPY ./yarn.lock ./
# COPY ./functions/package.json ./functions/.
# COPY ./functions/yarn.lock ./functions/.
