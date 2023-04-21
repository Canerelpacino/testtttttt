FROM nginx

# Benutzerdefinierte HTML-Datei hinzufügen
COPY nginx/test.html /usr/share/nginx/html/verteilte-anwendungen/

# Setzen Sie den Autor-Metatag in der HTML-Datei
RUN sed -i 's/<head>/<head><meta name="author" content="Max Mustermann, Mustafa Mustermann">/g' /usr/share/nginx/html/verteilte-anwendungen/test.html

# Öffnen Sie Port 80 für den Webserver
EXPOSE 80
