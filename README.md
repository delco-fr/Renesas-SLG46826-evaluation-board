# Carte d'évaluation pour Renesas SLG46826 (GreenPAK)

Ce projet Open Source Hardware propose une carte d'évaluation et de prototypage minimaliste pour le circuit mixte programmable **Renesas SLG46826** (famille GreenPAK™).

La carte expose l'ensemble des entrées/sorties (I/O) du composant sur un format pratique DIL-20 large (au pas de 2,54 mm, largeur 15,24 mm) et intègre un connecteur I²C Grove pour faciliter sa programmation in-situ.

---

## 📌 Caractéristiques principales

* **Composant cible :** Renesas SLG46826G (circuit intégré à signaux mixtes configurables).
* **Format pratique :** Brochage type DIL-20 large pour une insertion directe sur plaque d'essai (*breadboard*) ou support d'évaluation.
* **Interface de programmation :** Connecteur embarqué au standard **Grove I²C** pour une programmation, une configuration et un débogage simplifiés à l'aide d'une interface de programmation ou d'un microcontrôleur externe.
* **Stabilité :** Intégration des condensateurs de découplage requis pour les lignes d'alimentation (VDD et VDD2).

---

## 📂 Structure du dépôt

Le dépôt est organisé de la manière suivante :

* 📁 `pdf/` : Contient le schéma électronique complet de la carte au format PDF.
* 📁 `pics/` : Contient les photos du PCB, les rendus 3D et les illustrations du projet.
* 📁 `prod/` : Contient les fichiers nécessaires pour la production de la carte (par JLCPCB).
* 🛠️ *Fichiers sources de conception disponibles à la racine (conçu avec KiCad 10)*.

---

## 📐 Schéma Électronique

Le schéma électrique a été développé sous KiCad. Une version exportée prête à la lecture est disponible directement ici :
👉 **[Consulter le schéma PDF](pdf/ev_board_v1.0.pdf)** *(adapter le nom du fichier si nécessaire)*

### Aperçu du circuit
<img src="pics/Board_top_flat.png" width="50%">
![Schéma de la carte d'évaluation](pics/Board_top_flat.png)

---

## 🔗 Liens utiles & Documentation

* **Datasheet officielle :** Retrouvez toutes les spécifications techniques et électriques détaillées du circuit sur la [Page produit et Datasheet Renesas SLG46826](https://www.renesas.com/en/products/slg46824).
* **Logiciel de conception :** Le circuit a été routé à l'aide des outils de la suite [KiCad E.D.A.](https://kicad.org).

---

## ⚖️ Licence

Ce projet matériel est un matériel libre (*Open Hardware*). La conception de ce circuit imprimé est publiée sous licence :

**CERN Open Hardware Licence Version 2 - Strongly Reciprocal (CERN-OHL-S-2.0)**.

Vous êtes libre de reproduire, modifier et distribuer cette carte, sous réserve de maintenir les mêmes conditions de partage ouvertes pour vos propres modifications (réciprocité forte).

---
© 2026 Olivier DENIZOT - delco-fr.com | Open Hardware
