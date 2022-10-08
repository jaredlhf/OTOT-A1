FROM nginx

# Replaces default nginx config file
RUN rm  /etc/nginx/conf.d/default.conf
COPY default.conf /etc/nginx/conf.d/default.conf

# Copies html page into directory
COPY index.html /usr/share/nginx/html


