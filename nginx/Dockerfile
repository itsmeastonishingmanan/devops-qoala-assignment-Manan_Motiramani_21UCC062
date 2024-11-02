FROM nginx:latest
COPY nginx.conf /etc/nginx/nginx.conf
COPY ./html /usr/share/nginx/html/html
EXPOSE 80
CMD ["nginx", "-g", "daemon off;"]