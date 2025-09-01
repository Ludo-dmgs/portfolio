# On prend une image officielle Nginx (serveur web léger)
FROM nginx:alpine

# On supprime les fichiers par défaut de Nginx
RUN rm -rf /usr/share/nginx/html/*

# On copie ton site (les fichiers HTML/CSS/JS) dans le dossier public de Nginx
COPY . /usr/share/nginx/html

# On indique que le serveur utilise le port 80
EXPOSE 80

# On démarre Nginx
CMD ["nginx", "-g", "daemon off;"]
