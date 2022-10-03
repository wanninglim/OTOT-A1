# Define base image
FROM nginx:latest

# Copy static file over
COPY index.html /usr/share/nginx/html
COPY default.conf /etc/nginx/conf.d/default.conf

# Tell the port number the container should expose
EXPOSE 80