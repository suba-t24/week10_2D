# week10/frontend/Dockerfile

FROM nginx:1-alpine-slim

COPY nginx.conf /etc/nginx/conf.d/default.conf

COPY . /usr/share/nginx/html

EXPOSE 80

CMD ["nginx", "-g", "daemon off;"]
