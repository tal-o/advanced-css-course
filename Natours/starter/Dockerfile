FROM node:lts

WORKDIR /work

COPY package.json yarn.lock ./

RUN yarn

COPY . .

CMD [ "yarn", "watch:sass" ]
