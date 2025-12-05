# quartify_presentation

Présentation RevealJS du package R quartify, créée avec Quarto.

## 🎯 À propos

Cette présentation détaille le fonctionnement et l'utilisation du package R [quartify](https://github.com/ddotta/quartify), qui permet de convertir automatiquement des scripts R en documents Quarto.

## 🚀 Visualiser la présentation

La présentation est automatiquement déployée sur GitHub Pages via GitHub Actions :

👉 **[Voir la présentation](https://ddotta.github.io/quartify_presentation/)**

## 🛠️ Développement local

Pour prévisualiser la présentation localement :

```bash
quarto preview index.qmd
```

Pour générer la version HTML :

```bash
quarto render index.qmd
```

## 📦 Prérequis

- [Quarto](https://quarto.org/docs/get-started/) installé sur votre machine

## 🔄 Déploiement

Le déploiement sur GitHub Pages est automatique via GitHub Actions :
- Chaque push sur `main` déclenche le workflow
- Le workflow compile la présentation et la déploie

### Configuration requise

1. Aller dans Settings > Pages de votre repository
2. Sélectionner "GitHub Actions" comme source
3. Le workflow `.github/workflows/quarto-publish.yml` se chargera du reste

## 📝 Structure

```
quartify_presentation/
├── index.qmd              # Fichier principal de la présentation
├── _quarto.yml            # Configuration Quarto
├── styles.css             # Styles CSS personnalisés
├── .github/
│   └── workflows/
│       └── quarto-publish.yml  # Workflow GitHub Actions
└── README.md              # Ce fichier
```

## 📄 Licence

MIT

## 👤 Auteur

Damien Dotta
