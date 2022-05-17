FROM nginx

# Zmienna środowiskowa określa katalog docelowy przetworzonych szablonów
ENV NGINX_ENVSUBST_OUTPUT_DIR=/etc/nginx

# Umieszcza szablon konfiguracji w odpowiednim katalogu
COPY nginx.conf.template /etc/nginx/templates/nginx.conf.template