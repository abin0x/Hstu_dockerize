# # Use an Nginx image for serving the frontend
# FROM nginx:alpine

# # Copy the frontend files to Nginx's default HTML directory
# COPY . /usr/share/nginx/html

# # Expose the port Nginx will run on
# EXPOSE 80

# # Default command to start Nginx
# CMD ["nginx", "-g", "daemon off;"]




# Use the official Nginx image as the base
FROM nginx:alpine

# Copy the frontend files to the Nginx HTML directory
COPY . /usr/share/nginx/html

# Expose the Nginx port
EXPOSE 80

# Start the Nginx server
CMD ["nginx", "-g", "daemon off;"]
