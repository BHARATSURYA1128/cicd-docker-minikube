# frontend/Dockerfile
FROM nginx:alpine
COPY index.html /usr/share/nginx/html/index.html
# Add a custom nginx config to proxy API requests to the backend
COPY default.conf /etc/nginx/conf.d/default.conf