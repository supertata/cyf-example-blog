FROM node:12.2.0-alpine

RUN mkdir /app
WORKDIR /app

# add `/app/node_modules/.bin` to $PATH
# ENV PATH /app/node_modules/.bin:$PATH

COPY . ./
RUN npm install

# start app
CMD ["npm", "start"]
