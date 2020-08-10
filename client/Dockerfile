FROM mhart/alpine-node
RUN mkdir /client
WORKDIR /client
RUN apk update && apk upgrade && apk add --no-cache bash git
COPY . /client/
RUN yarn install
EXPOSE 3000
CMD ["yarn", "dev"] 