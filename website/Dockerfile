FROM nginx:latest

# Copy all website files into nginx html folder
COPY ./ /usr/share/nginx/html

# Expose port 80
EXPOSE 80

# Run nginx in the foregroundw
CMD ["nginx", "-g", "daemon off;"]

