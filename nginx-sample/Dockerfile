# Define base image
FROM nginx:latest

# Remove default nginx configurations
RUN rm /etc/nginx/nginx.conf /etc/nginx/conf.d/default.conf

# Copy static file over
COPY index.html /usr/share/nginx/html
COPY nginx.conf /etc/nginx/nginx.conf

# Tell the port number the container should expose
EXPOSE 80