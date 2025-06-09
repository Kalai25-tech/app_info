FROM nginx:latest
RUN sudo rm -rf /usr/share/nginx/html/*
COPY ./src-code/* /usr/share/nginx/html/
EXPOSE 80
CMD ["nginx", "-g", "daemon off;"]
