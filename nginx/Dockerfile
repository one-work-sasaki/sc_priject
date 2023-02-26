FROM nginx:1.21-alpine

RUN apk add --update vim

COPY nginx.conf /etc/nginx/nginx.conf

WORKDIR /var/www/html

COPY . .

EXPOSE 80

CMD ["nginx", "-g", "daemon off;"]