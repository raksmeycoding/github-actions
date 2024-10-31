# # Use the official Nginx image
# FROM nginx:alpine

# # Copy your Nginx configuration file
# COPY nginx.conf /etc/nginx/nginx.conf

# # Copy your web files
# COPY html /usr/share/nginx/html


# Use the official Nginx image
FROM nginx:alpine


# Copy custom HTML files to Nginx's default public directory
COPY ./html /usr/share/nginx/html

# Expose port 80
EXPOSE 80
