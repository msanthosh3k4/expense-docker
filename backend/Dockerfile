FROM node:20.19.5
WORKDIR /opt/backend
COPY package.json .
COPY *.js .
RUN npm install
DB_HOST="mysql"
CMD ["node","index.js"]