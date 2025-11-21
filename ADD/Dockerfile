FROM nginx:1.24
EXPOSE 80/tcp
RUN rm /usr/share/nginx/html/*
# ADD index.html /usr/share/nginx/html/
# ADD qi/ /usr/share/nginx/html/
ADD --unpack=true https://roboshop-artifacts.s3.amazonaws.com/frontend-v3.zip  /usr/share/nginx/html/
