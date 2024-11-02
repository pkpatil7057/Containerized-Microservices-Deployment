# Use the official Nginx image
FROM nginx:alpine

# Copy custom Nginx configuration
COPY nginx.conf /etc/nginx/nginx.conf

# Copy static HTML file to the default Nginx HTML directory
COPY index.html /usr/share/nginx/html

# Expose port 80
EXPOSE 80

