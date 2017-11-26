FROM nginx:latest

# Remove default configuration files
RUN rm /etc/nginx/conf.d/default.conf

# Copy our custom config files to Nginx Contatiner
COPY nginx.conf /etc/nginx
COPY site.conf /etc/nginx/conf.d
