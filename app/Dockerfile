# Use a lightweight web server
FROM nginx:alpine

# Copy static content to Nginx's default directory
COPY index.html /usr/share/nginx/html/

# Expose default Nginx port
EXPOSE 80

# Start Nginx
CMD ["nginx", "-g", "daemon off;"]
