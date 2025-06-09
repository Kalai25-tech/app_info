FROM nginx:latest
COPY ./src-code/*.html /usr/share/nginx/html/
EXPOSE 80
CMD ["nginx", "-g", "daemon off;"]