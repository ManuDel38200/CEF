# CEF - Centre Ennéagramme France

Site web statique pour le Centre Ennéagramme France, centre de formation à l'Ennéagramme basé à Lyon.

🌐 **Site original** : https://cef-enneagramme.com/

---

## 📁 Structure du projet

```
cef-site/
│
├── index.html                          # Page d'accueil
├── centres-enneagramme.html            # Les 3 centres d'énergie
├── a-propos.html                       # Présentation du CEF et Laurent Gardey
├── contact.html                        # Formulaire de contact
├── mentions-legales.html               # Mentions légales
├── politique-confidentialite.html      # Politique de confidentialité
│
├── css/
│   └── style.css                       # Feuille de styles principale (450+ lignes)
│
├── images/                             # (À compléter) Images du site
│
├── enneagramme/
│   ├── index.html                      # Page principale Ennéagramme
│   ├── definition-symbole.html         # Qu'est-ce que l'Ennéagramme ?
│   └── origine-histoire.html           # Origines et histoire
│
├── types-enneagramme/
│   ├── index.html                      # Vue globale des 9 profils
│   ├── type-1-perfectionniste.html
│   ├── type-2-altruiste.html
│   ├── type-3-battant.html
│   ├── type-4-tragico-romantique.html
│   ├── type-5-expert-observateur.html
│   ├── type-6-loyal-sceptique.html
│   ├── type-7-epicurien-optimiste.html
│   ├── type-8-chef-puissant.html
│   └── type-9-mediateur.html
│
└── formations-enneagramme/
    ├── index.html                      # Vue des 3 niveaux de formation
    ├── niveau-1.html                   # Formation Niveau 1
    ├── niveau-2.html                   # Formation Niveau 2
    └── entreprise.html                 # Formation en entreprise
```

**Total : 24 fichiers HTML + 1 fichier CSS**

---

## 🎨 Design

### Palette de couleurs

| Variable | Couleur | Usage |
|----------|---------|-------|
| `--primary` | `#2E5A88` | Bleu principal (titres, boutons) |
| `--primary-light` | `#4A7BA7` | Bleu clair (hover, dégradés) |
| `--primary-dark` | `#1e3a5f` | Bleu foncé (footer) |
| `--secondary` | `#E8B44B` | Jaune/or (accents, CTA secondaires) |
| `--text` | `#333` | Texte principal |
| `--text-light` | `#666` | Texte secondaire |
| `--bg-light` | `#f8f9fa` | Fond clair (sections) |
| `--bg-warm` | `#fdf8f3` | Fond chaud (citations) |

### Codes couleur des triades

| Centre | Couleur | Types |
|--------|---------|-------|
| Action (Colère) | Rouge `#c0392b` | 8, 9, 1 |
| Émotion (Reconnaissance) | Orange `#d35400` | 2, 3, 4 |
| Mental (Peur) | Bleu `#2980b9` | 5, 6, 7 |

### Composants UI

- **Header** : Navigation sticky avec dropdowns
- **Hero** : Bandeau dégradé bleu avec boutons CTA
- **Cards** : Effet hover (élévation + ombre)
- **Type cards** : Bordure colorée + badge numéro
- **Testimonials** : Guillemet décoratif + bordure jaune
- **Formation cards** : Header coloré + tableau tarifs
- **Footer** : 4 colonnes (Identité, Nav, Infos, Réseaux)

### Responsive

| Breakpoint | Adaptations |
|------------|-------------|
| `< 992px` | Navigation compactée |
| `< 768px` | Menu hamburger, grilles 1 colonne |
| `< 480px` | Tailles de police réduites |

---

## 📝 Contenu

### Informations clés

| Info | Valeur |
|------|--------|
| **Lieu** | Cap Sud Confluence, 10 rue Roland et Jacqueline de Pury, 69002 Lyon |
| **Formateur** | Laurent Gardey |
| **Facebook** | https://www.facebook.com/cefenneagramme |
| **LinkedIn** | https://linkedin.com/in/laurent-gardey-formateur-en-développement-personnel-67ab55192 |

### Tarifs formations

| Catégorie | Prix |
|-----------|------|
| Particulier | 275 € |
| Professionnel | 390 € |
| Étudiant | 210 € |
| Couple | 480 € |

### Dates formations 2025-2026

**Niveau 1 :**
- 7 et 8 février 2026
- 7 et 8 mars 2026
- 12 et 13 septembre 2026

**Niveau 2 :**
- 6 et 7 décembre 2025
- 11 et 12 avril 2026

**Niveau 3 :**
- 28 et 29 mars 2026

### Les 9 types de personnalité

| Type | Nom | Centre | Mots-clés |
|------|-----|--------|-----------|
| 1 | Perfectionniste | Action | Discipline, sens moral, rigueur, colère |
| 2 | Altruiste | Émotion | Serviabilité, empathie, orgueil |
| 3 | Battant | Émotion | Efficacité, persuasion, ambition |
| 4 | Tragico-romantique | Émotion | Originalité, mélancolie, créativité |
| 5 | Expert-observateur | Mental | Discrétion, observation, expertise |
| 6 | Loyal-Sceptique | Mental | Loyauté, vigilance, fiabilité |
| 7 | Épicurien-Optimiste | Mental | Optimisme, enthousiasme, gourmandise |
| 8 | Chef-puissant | Action | Leadership, protection, confrontation |
| 9 | Médiateur | Action | Diplomatie, harmonie, souplesse |

---

## 🚀 Utilisation

### Ouvrir en local

1. Extraire le ZIP dans un dossier
2. Ouvrir `index.html` dans un navigateur

### Modifier avec Claude Code

```bash
cd "D:\Création sites\CEF\cef-site"
claude
```

### Lancer un serveur local (optionnel)

```bash
# Python 3
python -m http.server 8000

# Node.js
npx serve

# PHP
php -S localhost:8000
```

Puis ouvrir http://localhost:8000

---

## 🔧 À compléter

### Images à ajouter

| Fichier | Description | Emplacement suggéré |
|---------|-------------|---------------------|
| `logo-cef.png` | Logo CEF | `images/` |
| `enneagramme-symbole.png` | Symbole de l'Ennéagramme | `images/` |
| `laurent-gardey.jpg` | Photo du formateur | `images/` |
| `type-1.png` à `type-9.png` | Illustrations des types | `images/types/` |

### Fonctionnalités à implémenter

- [ ] **Formulaire de contact fonctionnel** (Formspree, Netlify Forms, ou PHP)
- [ ] **Popup cookies** (RGPD)
- [ ] **Google Fonts** (optionnel, pour améliorer la typographie)
- [ ] **Favicon** (`favicon.ico`)
- [ ] **Meta Open Graph** (pour le partage réseaux sociaux)
- [ ] **Google Analytics** (si souhaité)

---

## 📄 Pages par section

### Navigation principale

| Page | URL | Description |
|------|-----|-------------|
| Accueil | `index.html` | Présentation générale, témoignages, formations |
| L'Ennéagramme | `enneagramme/index.html` | Introduction à l'Ennéagramme |
| Les 3 centres | `centres-enneagramme.html` | Action, Émotion, Mentalisation |
| Les 9 profils | `types-enneagramme/index.html` | Vue d'ensemble des 9 types |
| Formations | `formations-enneagramme/index.html` | Niveaux 1, 2, 3 |
| À propos | `a-propos.html` | Laurent Gardey, lieu |
| Contact | `contact.html` | Formulaire |

### Sous-pages Ennéagramme

| Page | URL |
|------|-----|
| Définition | `enneagramme/definition-symbole.html` |
| Histoire | `enneagramme/origine-histoire.html` |

### Sous-pages Types

| Type | URL |
|------|-----|
| Type 1 | `types-enneagramme/type-1-perfectionniste.html` |
| Type 2 | `types-enneagramme/type-2-altruiste.html` |
| Type 3 | `types-enneagramme/type-3-battant.html` |
| Type 4 | `types-enneagramme/type-4-tragico-romantique.html` |
| Type 5 | `types-enneagramme/type-5-expert-observateur.html` |
| Type 6 | `types-enneagramme/type-6-loyal-sceptique.html` |
| Type 7 | `types-enneagramme/type-7-epicurien-optimiste.html` |
| Type 8 | `types-enneagramme/type-8-chef-puissant.html` |
| Type 9 | `types-enneagramme/type-9-mediateur.html` |

### Sous-pages Formations

| Page | URL |
|------|-----|
| Niveau 1 | `formations-enneagramme/niveau-1.html` |
| Niveau 2 | `formations-enneagramme/niveau-2.html` |
| Entreprise | `formations-enneagramme/entreprise.html` |

---

## 🛠 Technologie

| Aspect | Choix |
|--------|-------|
| HTML | HTML5 sémantique |
| CSS | CSS3 natif (variables, grid, flexbox) |
| JavaScript | Vanilla JS minimal (menu toggle) |
| Framework | Aucun (site statique pur) |
| Liens | Relatifs (fonctionne sans serveur) |

---

## 📜 Licence

Contenu © 2021-2025 Centre Ennéagramme France (CEF)

---

## 📞 Contact

**Centre Ennéagramme France**  
Cap Sud Confluence  
10 rue Roland et Jacqueline de Pury  
69002 Lyon  

🌐 https://cef-enneagramme.com/  
📘 [Facebook](https://www.facebook.com/cefenneagramme)  
💼 [LinkedIn](https://linkedin.com/in/laurent-gardey-formateur-en-développement-personnel-67ab55192)
