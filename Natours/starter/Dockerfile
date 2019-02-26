FROM node:lts

WORKDIR /work

COPY package.json package.json

RUN yarn

COPY . .

ENTRYPOINT ["bash"]
