FROM node:alpine
WORKDIR /app
COPY package.json .
RUN npm install -g nodemon && npm install
COPY . .
EXPOSE 5000
CMD [ "npm","run","start"]