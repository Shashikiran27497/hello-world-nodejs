FROM node:16-alpine3.11

ARG TARGETPLATFORM=linux/amd64

COPY index.js index.js

COPY package.json package.json

RUN ["npm","install"]

CMD ["node","index.js"]
