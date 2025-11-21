FROM nginx:1.24
EXPOSE 80/tcp
RUN rm -rf /usr/share/nginx/html/*
ONBUILD ADD index.html /usr/share/nginx/html/
CMD ["nginx", "-g", "daemon off;"]