# Use the Nginx image from Docker Hub
FROM nginx:alpine

# Copy your website files to the default Nginx serve directory
COPY . /Personal-Website/share/nginx/html

# Expose port 80 to the outside
EXPOSE 80

# Start Nginx when the container starts
CMD ["nginx", "-g", "daemon off;"]
