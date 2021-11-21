FROM node:16-alpine

WORKDIR /usr/src/app

COPY package.json yarn.lock ./
RUN yarn install --prod

COPY . .

CMD ["yarn", "start"]
