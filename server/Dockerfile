FROM node

WORKDIR /app

COPY .  .

RUN npm install

COPY .env.example .env

EXPOSE 4000

CMD ["npm", "start"]
