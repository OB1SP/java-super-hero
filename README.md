# 🦸‍♂️ Superheroes, Villains & Anti-Heroes – Java Combat Simulation

Ce projet est une **simulation de combat en Java** basée sur la **programmation orientée objet (POO)**.  
Il met en scène des **Superhéros**, **Villains** et **Anti-Héros**, chacun avec des règles de combat spécifiques.

---

## 🎯 Objectif

L’objectif du projet est de :
- Comprendre et appliquer les **concepts fondamentaux de la POO**
- Manipuler l’**héritage**, le **polymorphisme** et la **redéfinition de méthodes**
- Simuler des combats avec des règles différentes selon le type de personnage

---

## 🧩 Concepts Java utilisés

- Classes et objets  
- Héritage (`extends`)  
- Méthodes redéfinies (`@Override`)  
- Encapsulation (`protected`, `public`)  
- `instanceof`  
- Redéfinition de `toString()`  
- Boucles et conditions  
- Simulation de combat

---

## 🦸 Personnages

### 🔹 Personnage (classe de base)
- `nom`
- `hp` (points de vie)
- `atk` (attaque)
- Méthodes :
  - `attaquer(Personnage p)`
  - `estKO()`
  - `toString()`

### 🦸 SuperHero
- Hérite de `Personnage`
- Inflige **80 % des dégâts** à un Villain

### 🦹 Villain
- Hérite de `Personnage`
- Inflige **20 % de dégâts supplémentaires** contre un SuperHero

### 🦸‍♂️😈 AntiHero
- Hérite de `Personnage`
- Inflige des dégâts normaux
- Subit **10 % de dégâts supplémentaires**, quel que soit l’attaquant

---

## ⚔️ Fonctionnalités

- Attaques entre personnages
- Calcul dynamique des dégâts selon le type
- Affichage de l’état des personnages
- Détection des personnages hors combat (KO)
- Simulation de combats en plusieurs tours

---

## ▶️ Exécution du projet

```bash
javac *.java
java Main
