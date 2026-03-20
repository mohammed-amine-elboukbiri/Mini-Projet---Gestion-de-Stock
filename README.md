# 📦 Mini Projet - Gestion de Stock

## 📖 Description

Ce projet est une application web développée avec **Spring Boot**, **Thymeleaf** et **MySQL** permettant de gérer un système de **gestion de stock**.

L’application permet de :

* Gérer les **fournisseurs**
* Gérer les **articles**
* Gérer les **mouvements de stock** (entrée / sortie)
* Suivre le stock en temps réel
* Détecter les articles en **seuil d’alerte**

---

## ⚙️ Technologies utilisées

* Java 21
* Spring Boot
* Spring Data JPA
* Thymeleaf
* MySQL
* Maven

---

## 🚀 Fonctionnalités principales

### 🧑‍💼 Gestion des fournisseurs

* Ajouter un fournisseur
* Modifier un fournisseur
* Supprimer un fournisseur
* Afficher la liste des fournisseurs

---

### 📦 Gestion des articles

* Ajouter un article
* Modifier un article
* Supprimer un article
* Associer un fournisseur à un article
* Définir un seuil d’alerte

---

### 🔄 Gestion des mouvements

* Ajouter un mouvement d'entrée (augmentation du stock)
* Ajouter un mouvement de sortie (diminution du stock)
* Vérifier le stock disponible avant sortie
* Mise à jour automatique du stock

---

### ⚠️ Gestion des alertes

* Détection automatique des articles en **stock critique**
* Condition :

```text
Stock <= Seuil d’alerte
```

---

## 🖥️ Interface utilisateur

### 📌 Formulaire Fournisseur

* Nom
* Ville

### 📌 Formulaire Article

* Code
* Désignation
* Catégorie
* Stock initial
* Seuil d’alerte
* Fournisseur

### 📌 Formulaire Mouvement

* Type (ENTREE / SORTIE)
* Quantité
* Date
* Article

---

## 🗄️ Base de données

Le projet utilise une base de données **MySQL** avec les entités suivantes :

* `Fournisseur`
* `Article`
* `Mouvement`

Relations :

* Un article appartient à un fournisseur
* Un mouvement est lié à un article

---

## Structure du code

<img width="437" height="818" alt="Screenshot 2026-03-20 at 01 08 37" src="https://github.com/user-attachments/assets/8943c340-6189-4cff-b9f5-9ef741c935da" />


---

## ▶️ Video demonstratif


https://github.com/user-attachments/assets/b3c0ee28-9d2b-4969-8bda-72b0eca1ea42


---

