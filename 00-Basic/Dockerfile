# Usa la imagen base de Apache
#FROM nexus.veridata.es:8443/httpd:latest
FROM httpd:latest

# Crea el archivo index.html con "Hello World!" dentro
RUN echo 'Hello World! Esto ha sido una actualización automática' > /usr/local/apache2/htdocs/index.html

# Expone el puerto 80
EXPOSE 80
