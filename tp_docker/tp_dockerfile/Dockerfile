FROM httpd:latest
EXPOSE 80
#COPY ./mon_fichier_de_configuration.conf /chemin/vers/le/fichier/de/configuration/apache.conf
#COPY ./mon_site_web /usr/local/apache2/htdocs/
CMD ["httpd", "-D", "FOREGROUND"]
COPY ./mon_contenu_web/ /usr/local/apache2/htdocs/
