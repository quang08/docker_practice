FROM node:20-alpine

RUN npm install -g nodemon

WORKDIR /app

COPY . .

RUN npm install

EXPOSE 3000
# required for docker desktop port mapping

CMD ["npm", "run", "dev"]