# Portfolio – Projet ECF4

## Auteur
Ludovic Domingues  
Projet réalisé dans le cadre de l’ECF4 (Développement Web & Web Mobile).


## 📌 Présentation
Ce projet est un **portfolio web** réalisé dans le cadre de l’ECF4 (Développement Web & Web Mobile).  
Il a pour but de présenter un site statique, containerisé avec Docker, et déployable facilement sur n’importe quel environnement.

Le projet met en avant :
- Une structure simple en **HTML/CSS/JS**.
- Une page d’accueil (`index.html`).
- Une page de contact avec **formulaire** et validation côté client (`contact.html`).
- Une documentation claire (`ECF4/DOCS_DOCKER.md`).
- Une image Docker hébergée sur Docker Hub.

---

## 🛠️ Installation locale (sans Docker)

1. Cloner le projet :
   ```bash
   git clone https://github.com/Ludo-dmgs/portfolio.git
   cd portfolio

## Image Docker

Ce projet est disponible sous forme d’image Docker publique.

### Version de développement (latest)
```bash
docker pull ludovic1441/portfolio:latest
docker run -d -p 8080:80 ludovic1441/portfolio:latest


