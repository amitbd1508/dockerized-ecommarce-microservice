FROM node:13
WORKDIR /app
COPY package.json /app
RUN npm install
COPY . /app
EXPOSE 4002
CMD npm start

