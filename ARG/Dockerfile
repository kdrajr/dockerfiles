ARG version=9
FROM almalinux:${version}
ARG version
RUN dnf module disable nginx -y && \
    dnf module enable nginx:${version} -y && \
    dnf install nginx -y
CMD ["nginx", "-g", "daemon off;"]