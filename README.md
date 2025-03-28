# 🌍 TheWinners — Site de guilde Horde (WoW 3.3.5)

Bienvenue sur le projet **TheWinners**, un site web développé en Symfony 7.2 pour notre guilde **Horde** sur serveur privé **World of Warcraft 3.3.5**.

## 📜 Présentation

Ce site a pour but de centraliser toutes les informations importantes liées à la guilde :

- 📚 Documentation pour les membres
- 📋 Formulaire de recrutement
- 📢 Annonces et actualités
- 💬 Messagerie instantanée interne
- 🛠️ Outils pour l’organisation des raids, loots, etc.

> Le projet est en cours de développement. N'hésitez pas à suivre les mises à jour !

---

## 🧱 Stack technique

- **Symfony 7.2**
- **PHP 8.3**
- **MySQL**
- **Doctrine ORM**
- **Twig / Bootstrap (ou autre selon les choix graphiques)**
- **Docker (facultatif selon config locale)**

---

## 🚧 État d'avancement

| Fonctionnalité             | Statut      |
|---------------------------|-------------|
| Page d'accueil            | ✅ En cours |
| Formulaire de recrutement | 🔜 À faire  |
| Espace membre             | 🔜 À faire  |
| Chat interne              | 🔜 À faire  |
| Back-office d'admin       | ✅ En cours |
| Authentification          | ✅ OK       |

---

## 🔧 Installation (locale)

```bash
git clone https://github.com/bouxi/TheWinners.git
cd TheWinners
composer install
symfony server:start
