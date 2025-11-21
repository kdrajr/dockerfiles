ARG version=9
FROM almalinux:${version}
RUN dnf module disable nginx -y && \
    dnf module enable nginx:1.24 -y && \
    dnf install nginx -y
CMD ["nginx", "-g", "daemon off;"]