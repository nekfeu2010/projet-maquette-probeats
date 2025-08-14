# Probeats E-commerce UI – Design (.fig) [![GitHub Repo](https://img.shields.io/badge/GitHub-thomas%2Fprobeats--ecommerce--ui-blue?logo=github)](https://github.com/thomas/probeats-ecommerce-ui)

## 🎯 Objectif

Ce repository contient la maquette Figma **desktop et mobile** du site e-commerce **Probeats**, conçue pour une expérience claire, moderne et responsive.

## 🔗 Maquette Figma

[📄 Voir sur Figma](https://www.figma.com/design/XRWBenCeNzh17vtuRefNbg/Probeat---devoir---fabio-montana--Community-?node-id=1-2&t=pb1HKG9DXux6iuTv-1)

> Assure-toi que le partage Figma est réglé sur *« Toute personne ayant le lien peut voir »* si le repo est public.

## 📦 Livrables

* `design/Probeat - devoir - fabio montana (Community).fig` : fichier Figma unique incluant les versions **desktop** et **mobile**.
* `design/exports/` *(optionnel)* : captures et exports PNG/JPG/PDF des écrans.
* `docs/preview.md` *(optionnel)* : guide visuel et notes sur la maquette.

## 🗂 Structure du projet

```
design/
  Probeat - devoir - fabio montana (Community).fig
  exports/
    desktop/
    mobile/
docs/
  preview.md
```

## 🖼 Pages & Frames

**Version Desktop :**

* Accueil
* Produit
* Commande
* À propos
* Assistance

**Version Mobile :**

* Accueil
* Produit
* Commande
* À propos
* Assistance

## 🧩 Composants & styles

* **Typographie** : Barlow (titres, textes)
* **Couleurs** : palette extraite de la maquette (primaire, secondaire, neutres)
* **Boutons** : défaut, survol, actif
* **Champs de formulaire** : normal, focus, erreur
* **Cartes produit** : photo, nom, prix, CTA
* **Header & footer** : variantes desktop et mobile
* **Icônes** : pack cohérent (style minimaliste)

## 📷 Aperçu

### Desktop

![Accueil](design/exports/desktop/accueil.png)
![Produit](design/exports/desktop/produit.png)
![Commande](design/exports/desktop/commande.png)
![À propos](design/exports/desktop/apropos.png)
![Assistance](design/exports/desktop/assistance.png)

### Mobile

![Accueil](design/exports/mobile/accueil.png)
![Produit](design/exports/mobile/produit.png)
![Commande](design/exports/mobile/commande.png)
![À propos](design/exports/mobile/apropos.png)
![Assistance](design/exports/mobile/assistance.png)

> ⚠️ Les chemins ci-dessus doivent correspondre **exactement** aux noms des fichiers (casse incluse) présents dans le repo.

## 🔎 Ouvrir le fichier `.fig`

1. Ouvrir Figma → `File > Import…`
2. Sélectionner `design/Probeat - devoir - fabio montana (Community).fig`

## 🧰 Export d’aperçus (optionnel)

Depuis Figma :

* Sélectionner une frame → **Export** → PNG/JPG/PDF
* Enregistrer dans `design/exports/desktop` ou `design/exports/mobile`

## 🧱 Versioning

* Les images et/ou `.fig` lourds peuvent être suivis avec **Git LFS**.

  ```bash
  git lfs install
  git lfs track "*.png" "*.jpg" "*.fig"
  git add .gitattributes
  git commit -m "chore(lfs): track images & fig"
  git push origin main
  ```
* Historique des changements dans `CHANGELOG.md` *(optionnel)*.

## 📌 Repo GitHub

[https://github.com/thomas/probeats-ecommerce-ui](https://github.com/thomas/probeats-ecommerce-ui)

## 🚀 Commandes utiles

```bash
# Ajouter tous les fichiers (captures, .fig, docs)
git add .

# Commit
git commit -m "feat: ajout des captures d’écran desktop et mobile"

# Pousser sur GitHub
git push origin main
```

---

> **Note** : Les antislashs `\(` ou `\)` dans les liens/chemins empêchent l’affichage des images en Markdown GitHub. Assure-toi que la syntaxe est de la forme `![alt](chemin/vers/fichier.png)` **sans** antislashs.

