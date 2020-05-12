FROM node:13.12.0-alpine

# set working directory
WORKDIR /usr/src/app

# install app dependencies
COPY package.json ./
RUN yarn
RUN yarn install

# add app
COPY . ./

# start app
CMD ["yarn", "start"]