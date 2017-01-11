FROM node:alpine
RUN apk add --no-cache git
ENV PATH $PATH:./node_modules/.bin
VOLUME /work
WORKDIR /work
COPY package.json package.json
RUN npm i -D
CMD ["npm"]