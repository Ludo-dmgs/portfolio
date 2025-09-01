# Je pars d’une image officielle Nginx (un serveur web léger et rapide)
FROM nginx:alpine

# Je supprime les fichiers par défaut fournis avec Nginx pour repartir propre
RUN rm -rf /usr/share/nginx/html/*

# Je copie mon site (HTML / CSS / JS) dans le dossier public de Nginx
COPY . /usr/share/nginx/html

# J’indique que mon serveur écoutera sur le port 80
EXPOSE 80

# Je lance Nginx en mode "premier plan" pour que le conteneur reste actif
CMD ["nginx", "-g", "daemon off;"]
