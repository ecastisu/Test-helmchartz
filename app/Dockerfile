FROM nginx:latest

# Limpiar el contenido por defecto de NGINX
RUN rm -rf /usr/share/nginx/html/*

# Copiar TODO el sitio (carpeta web) al docroot de NGINX
COPY ./sitio /usr/share/nginx/html/

EXPOSE 80
CMD ["nginx", "-g", "daemon off;"]
