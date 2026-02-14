FROM nginx:latest

# Copy custom main configuration file
COPY nginx.conf /etc/nginx/nginx.conf

# Copy custom site configuration if needed (Nginx default usually includes /etc/nginx/conf.d/*.conf)
COPY default.conf /etc/nginx/conf.d/default.conf

EXPOSE 80 443

CMD ["nginx", "-g", "daemon off;"]