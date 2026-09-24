# Candidature - Ayden Ganofski

Site web personnel conçu dans le cadre de ma candidature pour le stage **"Développement web, IA & gouvernance numérique"** chez **Alpha to Omega**.

**Lien du site :** https://site-presentation-ag.pages.dev/

> **Notes d'affichage :**
> - Le site s'adapte automatiquement au thème de votre navigateur web (le thème clair est conseillé pour une lecture optimale).
> - Les animations au défilement reposent sur la spécification moderne *CSS Scroll-driven Animations* (support natif optimal sur Chrome, Edge et navigateurs Chromium).
---

## Contexte du projet

Ce projet remplace le format CV/lettre classique pour présenter de manière interactive :
- Mon profil d'étudiant en 2ᵉ année de BUT Informatique à l'IUT de Blagnac.
- Mes réalisations académiques et projets personnels.
- Ma compréhension des missions proposées par Alpha to Omega et mes motivations pour le stage.

---

## Stack technique et Hébergement

- **Langages :** HTML5 sémantique (validé W3C), CSS3 moderne.
- **Architecture :** Site statique multipage sans dépendances lourdes, optimisé pour les performances.
- **Hébergement & Déploiement continu :** [Cloudflare Pages](https://pages.cloudflare.com/) relié à ce dépôt GitHub.

---

## Structure du dépôt

```text
├── index.html            # Présentation du profil, parcours et compétences
├── projets.html          # Détail des projets académiques et personnelles
├── motivations.html      # Analyse de l'offre et motivations pour Alpha to Omega
├── contact.html          # Coordonnées directes et liens professionnels
├── mentions-legales.html # Informations réglementaires (LCEN / Hébergement)
├── credit.html           # Attribution des ressources graphiques et licences
├── styles/
│   ├── base.css          # Variables, typographies, header/footer et styles partagés
│   └── ...               # Styles spécifiques à chaque page
└── images/               # Médias(WebP, GIF)
