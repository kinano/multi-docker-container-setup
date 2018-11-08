FROM node:alpine

WORKDIR '/app'

COPY ./package.json .

RUN npm install

COPY . .

# This is the production npm start command
CMD ["npm", "run", "start"]