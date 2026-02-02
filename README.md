# TP2 — Données scannées sous CATIA V5 (DSE & QSR)

Ce TP porte sur l’exploitation de **données scannées 3D** dans **CATIA V5**, en utilisant les ateliers  
**Digitized Shape Editor (DSE)** et **Quick Surface Reconstruction (QSR)**.

L’objectif est de suivre une **procédure globale et structurée** permettant de passer d’un **scan 3D**
à une **pièce CAO exploitable**, jusqu’à la création d’un solide lorsque cela est possible.

---

## Objectif pédagogique

À l’issue du TP, l’étudiant doit être capable de :

- importer des données scannées dans CATIA V5 ;
- nettoyer et préparer un nuage de points ;
- générer et réparer un maillage ;
- reconstruire des surfaces CAO à partir d’un maillage ;
- comprendre les conditions nécessaires à la création d’un solide.

L’accent est mis sur la **méthodologie** et la **logique des ateliers**, et non sur l’obtention d’un modèle parfait.

---

## Contenu du TP

Le TP suit une chaîne de traitement en **4 grandes étapes** :

### 1. Nuage de points — *Digitized Shape Editor (DSE)*
- Import des données scannées
- Réduction de la densité (Filter)
- Suppression des zones parasites (Remove)

### 2. Maillage — *Digitized Shape Editor (DSE)*
- Création du maillage à partir du nuage
- Nettoyage du maillage (Mesh Cleaner)
- Remplissage des trous si nécessaire (Fill Holes)

### 3. Reconstruction de surfaces — *Quick Surface Reconstruction (QSR)*
- Génération automatique de surfaces
- Possibilité de reconstruction manuelle par courbes
- Adaptation des surfaces par courbes ou primitives géométriques

### 4. Vers le solide — *QSR → Part Design*
- Création des intersections entre surfaces
- Ajustement des surfaces (scinder, tronquer, raccorder)
- Fermeture des surfaces pour obtenir un solide, si possible

---

## Données fournies

Le TP s’appuie sur les fichiers suivants :

- **`TP2.pdf`**  
  → Protocole détaillé du TP (slides)

- **`simple_geometry.stl`**  
  → Géométrie simple, destinée à la prise en main et à la validation de la procédure

- **`complex_geometry.stl`**  
  → Géométrie plus complexe, mettant en évidence les limites et difficultés de la reconstruction

---

## Travail attendu

Les étudiants doivent :

- suivre la procédure décrite dans le protocole `TP2.pdf` ;
- appliquer la chaîne complète sur au moins une géométrie ;
- identifier les difficultés rencontrées (maillage, surfaces, fermeture) ;
- justifier les choix effectués lors du traitement des données.

L’obtention d’un solide final n’est **pas obligatoire** si la géométrie ou la qualité du scan ne le permet pas.

---

## Message clé

> Le TP2 vise avant tout la compréhension de la **chaîne de traitement des données scannées**  
> et la maîtrise des **ateliers CATIA**, plus que la production d’un modèle CAO parfait.

---

## Contexte pédagogique

**BE de numérisation 3D**  
Licence MICAP – Métrologie Dimensionnelle et Qualité  
Université Sorbonne Paris Nord  
LURPA – ENS Paris-Saclay
