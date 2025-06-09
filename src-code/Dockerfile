FROM nginx:latest
RUN sudo rm -rf /usr/share/nginx/html/*
COPY ./src-code/*.html /usr/share/nginx/html/
EXPOSE 80
CMD ["nginx", "-g", "daemon off;"]