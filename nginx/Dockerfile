# development environment
FROM nginx:1.16.0-alpine
RUN rm /etc/nginx/conf.d/default.conf
COPY ./conf.d/app.conf /etc/nginx/conf.d
EXPOSE 8011
CMD ["nginx", "-g", "daemon off;"]