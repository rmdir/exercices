# Use a lightweight production-grade web server
FROM nginx:alpine

# Copy the HTML file to the default Nginx public directory
# Assuming your file is named index.html
COPY ./index.html /usr/share/nginx/html/index.html

# Expose port 80 for the web traffic
EXPOSE 80

# Start Nginx
CMD ["nginx", "-g", "daemon off;"]
