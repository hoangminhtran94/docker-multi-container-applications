FROM node

WORKDIR /app

COPY . .

RUN npm install

ENV PORT 80
ENV MONGODB_USERNAME=hoang
ENV MONGODB_PASSWORD=secret

EXPOSE $PORT

CMD ["npm","start"]