FROM nginx:1.24
EXPOSE 80/tcp
RUN rm /usr/share/nginx/html/*
ONBUILD ADD index.html /usr/share/nginx/html/