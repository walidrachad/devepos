# Use an official Nginx runtime as a parent image
FROM nginx:alpine

# Copy the Nginx configuration file
COPY nginx.conf /etc/nginx/nginx.conf

# Copy the Angular build output to the Nginx document root
COPY html/ /usr/share/nginx/html

EXPOSE 80

# CMD ["nginx", "-g", "daemon off;"]
