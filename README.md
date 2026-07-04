# 🌐 MailSeed — Cartographiez l'utilisation de vos adresses email

[![AdonisJS](https://img.shields.io/badge/Framework-AdonisJS%20v6-5a45ff?style=flat-square&logo=adonisjs)](https://adonisjs.com/)
[![Tailwind CSS](https://img.shields.io/badge/CSS-Tailwind%20v4-38bdf8?style=flat-square&logo=tailwindcss)](https://tailwindcss.com/)
[![Vite](https://img.shields.io/badge/Bundler-Vite-646cff?style=flat-square&logo=vite)](https://vite.dev/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green?style=flat-square)](LICENSE)

> **MailSeed** (anciennement _MailMap_) est une application web full-stack permettant de **centraliser**, **organiser** et **cartographier** l'utilisation de toutes vos adresses email.

Que vous possédiez plusieurs boîtes mail personnelles, professionnelles, universitaires ou dédiées aux inscriptions, MailSeed vous permet de retrouver instantanément **quelle adresse est utilisée sur quel service**.

---

## 📖 Sommaire

- [🎯 Le projet](#-le-projet)
- [🚀 Fonctionnalités](#-fonctionnalités)
- [🛠️ Stack technique](#️-stack-technique)
- [📂 Architecture](#-architecture)
- [⚙️ Installation](#️-installation)
- [🚀 Lancement du projet](#-lancement-du-projet)
- [📌 Roadmap](#-roadmap)
- [👤 Auteur](#-auteur)
- [📄 Licence](#-licence)

---

# 🎯 Le projet

Aujourd'hui, nous possédons souvent plusieurs adresses email :

- 📧 Adresse personnelle
- 💼 Adresse professionnelle
- 🛒 Adresse dédiée aux achats
- 📨 Adresse "junk mail"
- 🎓 Adresse étudiante
- 🔐 Adresse réservée aux comptes sensibles

Après plusieurs années, il devient presque impossible de se souvenir :

- Quel email est utilisé pour Netflix ?
- Avec quelle adresse suis-je inscrit sur Kraken ?
- Quel compte est associé à LinkedIn ?
- Où ai-je créé mon compte GitHub ?
- Quelle adresse dois-je utiliser pour réinitialiser mon mot de passe ?

**MailSeed** répond précisément à ce problème.

L'application agit comme une véritable **cartographie de votre identité numérique**, en reliant chacune de vos adresses email aux plateformes où elles sont utilisées.

---

# 🚀 Fonctionnalités

## 📧 Gestion des adresses email

- Ajouter plusieurs adresses email
- Les organiser facilement
- Les modifier ou supprimer
- Identifier rapidement leur utilisation

---

## 🗂️ Gestion des plateformes

Associez chaque adresse à des plateformes comme :

- Netflix
- Amazon
- GitHub
- LinkedIn
- Kraken
- Revolut
- Google
- Discord
- Steam
- Spotify
- etc.

Chaque plateforme est liée à **une seule adresse email**, ce qui permet de retrouver immédiatement le bon compte.

---

## 🔍 Recherche instantanée

Recherchez :

- un nom de plateforme
- une adresse email
- un mot-clé

Et retrouvez immédiatement l'association correspondante.

---

## 📊 Tableau de bord

Une interface moderne permettant de visualiser :

- toutes vos adresses
- tous les services associés
- le nombre de plateformes par email
- une navigation claire sous forme de cartes

---

## 🔐 Gestion sécurisée

Le projet est conçu pour fonctionner avec un espace utilisateur sécurisé.

À terme :

- authentification
- chiffrement
- gestion multi-utilisateur

---

# 🛠️ Stack technique

Le projet repose sur des technologies modernes.

| Technologie             | Description                             |
| ----------------------- | --------------------------------------- |
| **AdonisJS v6**         | Framework Backend Node.js               |
| **TypeScript**          | Typage strict                           |
| **EdgeJS**              | Moteur de templates                     |
| **Tailwind CSS v4**     | UI moderne                              |
| **Vite**                | Bundler ultra rapide                    |
| **Node.js**             | Runtime JavaScript                      |
| **SQLite / PostgreSQL** | Base de données (selon l'environnement) |

---

# 📂 Architecture

```text
mailseed/
│
├── app/
│   ├── Controllers/
│   ├── Models/
│   ├── Middleware/
│   ├── Services/
│   └── Validators/
│
├── config/
├── database/
├── resources/
│   ├── views/
│   ├── css/
│   └── js/
│
├── start/
├── public/
├── tests/
│
├── .env
├── package.json
└── README.md
```

---

# ⚙️ Installation

## 1. Cloner le projet

```bash
git clone https://github.com/votre-compte/mailseed.git
```

```bash
cd mailseed
```

---

## 2. Installer les dépendances

```bash
npm install
```

---

## 3. Configurer l'environnement

```bash
cp .env.example .env
```

Configurez ensuite votre base de données dans le fichier `.env`.

---

## 4. Lancer les migrations

```bash
node ace migration:run
```

---

## 5. Démarrer le serveur

```bash
node ace serve --watch
```

Le projet sera disponible sur :

```
http://localhost:3333
```

---

# 🚀 Commandes utiles

### Développement

```bash
node ace serve --watch
```

### Compilation des assets

```bash
npm run dev
```

### Build production

```bash
npm run build
```

### Lancer les migrations

```bash
node ace migration:run
```

### Réinitialiser la base

```bash
node ace migration:refresh
```

---

# 📌 Roadmap

## Version 1

- [x] Gestion des emails
- [x] Gestion des plateformes
- [x] Dashboard
- [x] Recherche rapide

---

## Version 2

- [ ] Authentification
- [ ] Comptes utilisateurs
- [ ] Catégories
- [ ] Icônes automatiques des plateformes
- [ ] Statistiques

---

## Version 3

- [ ] Import CSV
- [ ] Export CSV
- [ ] Synchronisation cloud
- [ ] API REST
- [ ] Application mobile

---

# 💡 Cas d'utilisation

MailSeed est particulièrement utile si vous :

- possédez plusieurs adresses email ;
- utilisez des dizaines, voire des centaines de services en ligne ;
- oubliez régulièrement quelle adresse est associée à un compte ;
- souhaitez mieux organiser votre identité numérique ;
- cherchez un tableau de bord simple pour gérer vos comptes.

---

# 👤 Auteur

Développé avec ❤️ par **Nuno Fernandes**

**Full-Stack Engineer**

Si vous souhaitez échanger autour du projet, proposer une amélioration ou collaborer, n'hésitez pas à me contacter.

---

# 🤝 Contribution

Les contributions sont les bienvenues !

1. Forkez le projet.
2. Créez une branche :

```bash
git checkout -b feature/ma-feature
```

3. Committez vos modifications :

```bash
git commit -m "Ajout de ma fonctionnalité"
```

4. Poussez votre branche :

```bash
git push origin feature/ma-feature
```

5. Ouvrez une Pull Request.

---

# 📄 Licence

Ce projet est distribué sous licence **MIT**.

Vous êtes libre de :

- utiliser le projet ;
- le modifier ;
- le distribuer ;
- l'adapter à vos besoins.

Voir le fichier **LICENSE** pour plus d'informations.

---

**MailSeed** 🌱

_Cartographiez votre identité numérique, une adresse email à la fois._
