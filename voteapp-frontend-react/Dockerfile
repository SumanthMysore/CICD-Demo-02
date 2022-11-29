# FROM nginx
# COPY build /usr/share/nginx/html


FROM node:18-alpine3.15

WORKDIR /app

COPY . .

RUN npm ci

EXPOSE 3000

CMD ["npm", "run", "start"]