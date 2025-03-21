# Portfolio Professionnel de Hugo Biegas

Ce dépôt contient le code source de mon portfolio professionnel, présentant mes compétences, projets et expériences en tant que développeur web, mobile et spécialiste en cybersécurité.

## Aperçu

Ce portfolio a été conçu pour mettre en valeur mon expertise technique et offrir une expérience utilisateur optimale. Le site est entièrement responsive et propose un mode sombre/clair pour un confort de lecture optimal.

## Caractéristiques

- **Design moderne et responsive** : Adaptation parfaite à tous les appareils (desktop, tablette, mobile)
- **Mode sombre/clair** : Basculement facile entre les thèmes
- **Animations fluides** : Amélioration de l'expérience utilisateur
- **Performance optimisée** : Temps de chargement minimal
- **Compatible avec tous les navigateurs modernes** : Chrome, Firefox, Safari, Edge
- **Accessibilité** : Respect des bonnes pratiques d'accessibilité web
- **SEO friendly** : Structure sémantique et balises méta optimisées

## Structure du Projet

```
portfolio-hugo-biegas/
│
├── assets/
│   ├── css/
│   │   ├── main.css            # Styles principaux
│   │   ├── animations.css      # Animations
│   │   ├── responsive.css      # Styles responsifs
│   │   └── dark-mode.css       # Styles du mode sombre
│   ├── js/
│   │   ├── main.js             # JavaScript principal
│   │   ├── projects.js         # Fonctionnalités de la page projets
│   │   └── dark-mode.js        # Gestion du mode sombre
│   ├── img/                    # Images et ressources graphiques
│   └── fonts/                  # Polices personnalisées
│
├── index.html                  # Page d'accueil
├── projects.html               # Page des projets
├── skills.html                 # Page des compétences
├── experience.html             # Page d'expérience
├── contact.html                # Page de contact
└── README.md                   # Documentation
```

## Technologies Utilisées

- **HTML5** : Structure sémantique
- **CSS3** : Styles modernes (Flexbox, Grid, animations)
- **JavaScript** : Interactivité et fonctionnalités dynamiques
- **Firebase** : Stockage des messages du formulaire de contact
- **Font Awesome** : Icônes vectorielles
- **Google Fonts** : Typographie

## Fonctionnalités Principales

1. **Navigation intuitive** : Menu responsive avec état actif et animation fluide
2. **Page d'accueil** : Présentation concise et mise en avant des compétences clés
3. **Portfolio de projets** : Galerie interactive avec filtrage par catégorie
4. **Section compétences** : Visualisation des niveaux de maîtrise par domaine
5. **Expérience professionnelle** : Chronologie visuelle du parcours
6. **Page de contact** : Formulaire fonctionnel connecté à Firebase pour le stockage des messages
7. **Thème sombre/clair** : Préférence utilisateur mémorisée

## Installation et Utilisation

1. Clonez ce dépôt :
   ```bash
   git clone https://github.com/HugoBiegas/portfolio.git
   ```

2. Ouvrez le fichier `index.html` dans votre navigateur pour explorer le site localement.

3. Pour déployer sur un serveur web, transférez simplement tous les fichiers vers votre hébergement.

4. Pour que le formulaire de contact fonctionne, vous devrez configurer votre propre projet Firebase :
   - Créez un projet sur [Firebase Console](https://console.firebase.google.com/)
   - Activez Firestore Database
   - Remplacez la configuration Firebase dans le fichier `contact.html` avec vos propres identifiants
   - Configurez les règles de sécurité appropriées pour votre base de données

## Personnalisation

Si vous souhaitez adapter ce portfolio à votre usage personnel :

1. Modifiez les informations personnelles dans chaque fichier HTML
2. Remplacez les images dans le dossier `assets/img/`
3. Ajustez les couleurs dans les variables CSS (fichier `main.css`)
4. Mettez à jour les liens de vos réseaux sociaux et projets
5. Personnalisez la configuration Firebase pour le formulaire de contact

## Bonnes Pratiques Implémentées

- **Principes SOLID** : Architecture modulaire et maintenable
- **Performance** : Optimisation des ressources et temps de chargement
- **Sécurité** : Protection contre les vulnérabilités web courantes (XSS, CSRF, injections)
- **Accessibilité** : Conformité aux normes WCAG
- **SEO** : Structure sémantique et balises méta optimisées
- **Responsive Design** : Adaptation fluide à tous les appareils
- **Mode sombre/clair** : Respect des préférences utilisateur

## Sécurité du Formulaire de Contact

Le formulaire de contact implémente plusieurs mesures de sécurité :
- Validation côté client et côté serveur des données saisies
- Protection contre les attaques CSRF
- Limitation du nombre de soumissions par IP
- Stockage sécurisé des données dans Firebase Firestore
- Gestion intelligente des erreurs

## Maintenance et Mises à Jour

Ce portfolio est régulièrement maintenu pour :
- Garder les dépendances à jour
- Améliorer les performances
- Ajouter de nouveaux projets
- Mettre à jour les informations professionnelles

## Compatibilité Navigateurs

- Chrome (dernières versions)
- Firefox (dernières versions)
- Safari (dernières versions)
- Edge (dernières versions)
- Opera (dernières versions)

## Contact

Pour toute question ou suggestion concernant ce portfolio, n'hésitez pas à me contacter :

- Email : Contact.Hugo.Biegas@gmail.com
- LinkedIn : [linkedin.com/in/hugo-biegas](https://linkedin.com/in/hugo-biegas)
- GitHub : [github.com/HugoBiegas](https://github.com/HugoBiegas)

---

Développé avec ❤️ par Hugo Biegas