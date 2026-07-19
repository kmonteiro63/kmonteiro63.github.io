# Portfolio — Kevin Monteiro

Portfolio personnel présentant mon parcours de technicien en informatique industrielle et mon activité d'entrepreneur individuel (L'Atelier Numérique KM), destiné aux recruteurs et clients potentiels.

🔗 **Site en ligne :** https://kmonteiro63.github.io

## Aperçu

Le site présente :

- **À propos de moi** — présentation personnelle et parcours
- **CV** — expériences professionnelles, formation, compétences techniques, sous forme de mise en page type CV (sidebar + timeline) + CV téléchargeable condensée
- **Projets** — alternance et SAÉ réalisées durant le BUT Informatique
- **Entreprenariat** — présentation de L'Atelier Numérique KM - ma micro-entreprise (réparation, montage PC, services numériques, développement) - (https://atelier-numerique-km.fr)
- **Objectifs** — axes de développement de compétences (dev logiciel, réseaux, cybersécurité, électronique embarquée, infrastructure, informatique industrielle)
- **Contact** — formulaire d'envoi de mail (via `mailto:`) et coordonnées

## Stack technique

- HTML5 / CSS3
- [Bootstrap 5.2.3](https://getbootstrap.com/) (via CDN)
- Thème de base : [Start Bootstrap – Grayscale](https://startbootstrap.com/theme/grayscale) (licence MIT)
- [Font Awesome 6.3.0](https://fontawesome.com/) (icônes)
- Google Fonts — Varela Round, Nunito
- JavaScript vanilla (formulaire de contact, compteur de caractères)

## Structure du projet

```
.
├── index.html
├── css/
│   ├── styles.css       # Styles globaux (thème Grayscale personnalisé)
│   └── cv.css            # Styles spécifiques à la section CV
├── js/
│   └── scripts.js        # Scripts globaux (nav, scroll, etc.)
├── assets/
│   ├── logo.jpg
│   ├── CV_Kevin_Monteiro.pdf
│   └── img/               # Images (projets, entreprise, logo, etc.)
└── photo.jpg
```


## Formulaire de contact

Le formulaire de contact ne passe pas par un backend : il génère un lien `mailto:` pré-rempli avec le message saisi, qui ouvre le client mail par défaut de l'utilisateur.

## Contact

- 📧 atelier.numerique.km@gmail.com
- ☎️ (+33) 06.10.98.15.15
- 📍 Clermont-Ferrand, France