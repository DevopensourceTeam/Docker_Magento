FROM nginx:latest

COPY default.conf /etc/nginx/conf.d
COPY nginx.auth /var/nginx/nginx.auth
RUN chown nginx:root /var/nginx/nginx.auth && \
  chmod 600 /var/nginx/nginx.auth