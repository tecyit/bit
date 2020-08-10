FROM mhart/alpine-node
WORKDIR /usr/src/app/actions
COPY package.json /usr/src/app/actions
RUN yarn 
COPY . /usr/src/app/actions
RUN yarn build
EXPOSE 4000
CMD yarn start 
