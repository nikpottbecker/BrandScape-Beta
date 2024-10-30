# Basis-Image
FROM nginx:alpine

# Kopiere die Website-Dateien
COPY . /usr/share/nginx/html/

# Konfiguriere NGINX
COPY nginx.conf /etc/nginx/conf.d/default.conf

# Port 80 exponieren
EXPOSE 80 