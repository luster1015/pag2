# Usa la imagen oficial de httpd
FROM httpd

# Actualiza los paquetes e instala vim y bind9
RUN apt-get update && apt-get install -y vim bind9

# Copia tu página web al directorio correcto en el contenedor
COPY html /usr/local/apache2/htdocs/


