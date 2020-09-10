FROM nginx:1.19.2-alpine
COPY /html_files /usr/share/nginx/html
COPY ./default.conf /etc/nginx/conf.d/default.conf
EXPOSE 22222
CMD ["nginx", "-g", "daemon off;"] 