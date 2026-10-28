FROM nginx:stable

# Remove o server padrão para não conflitar com o default_server do nginx.conf
RUN rm -f /etc/nginx/conf.d/default.conf

COPY nginx.conf /etc/nginx/nginx.conf
COPY dist/ /usr/share/nginx/html/

EXPOSE 80
