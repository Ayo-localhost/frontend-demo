FROM node:22-alpine

WORKDIR /app

COPY ./frontend-demo ./

RUN npm install

RUN npm run build

EXPOSE 8080

CMD ["npm", "start", "--", "--port", "8080", "--host", "0.0.0.0"]
