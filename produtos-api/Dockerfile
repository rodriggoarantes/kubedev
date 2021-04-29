FROM node:14-alpine
ENV NODE_ENV=production
WORKDIR /app

COPY ./src/package*.json ./
RUN npm install

COPY ./src ./

EXPOSE 8080

CMD [ "node", "app.js" ] 