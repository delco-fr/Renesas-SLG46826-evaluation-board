# Carte d'évaluation pour Renesas SLG46826 (GreenPAK)<br>Evaluation Board for Renesas SLG46826 (GreenPAK)

Ce dépôt contient la documentation et les fichiers de conception d'une carte d'évaluation pour le Renesas SLG46826, disponible en français et en anglais.  
This repository contains the documentation and design files for a Renesas SLG46826 evaluation board, available in both French and English.

---

## 🌍 Language / Langue

* [Français (#version-française)](#version-française)
* [English (#english-version)](#english-version)

---

<div id="version-française"></div>

# Version Française

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
 **[Consulter le schéma PDF](pdf/ev_board_v1.0.pdf)**

### Aperçu du circuit
<p align="center">
  <img src="pics/Board_top_flat.png" width="50%">
</p>

---

## 💡 Exemple

*(Ajoutez ici vos exemples d'utilisation, de code ou d'application pour le SLG46826)*

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

<div id="english-version"></div>

# English Version

This Open Source Hardware project features a minimalist evaluation and prototyping board for the **Renesas SLG46826** programmable mixed-signal matrix (GreenPAK™ family).

The board breaks out all of the component's inputs/outputs (I/Os) into a convenient wide DIL-20 format (2.54 mm pitch, 15.24 mm width) and integrates a Grove I²C connector to facilitate in-system programming.

---

## 📌 Main Features

* **Target Component:** Renesas SLG46826G (configurable mixed-signal integrated circuit).
* **Convenient Format:** Wide DIL-20 pinout for direct insertion into a breadboard or evaluation socket.
* **Programming Interface:** Onboard **Grove I²C** standard connector for simplified programming, configuration, and debugging using a programming interface or an external microcontroller.
* **Stability:** Integrated decoupling capacitors required for the power supply lines (VDD and VDD2).

---

## 📂 Repository Structure

The repository is organized as follows:

* 📁 `pdf/`: Contains the complete electronic schematic of the board in PDF format.
* 📁 `pics/`: Contains PCB photos, 3D renders, and project illustrations.
* 📁 `prod/`: Contains the files required for manufacturing the board (by JLCPCB).
* 🛠️ *Design source files available at the root (designed with KiCad 10)*.

---

## 📐 Electronic Schematic

The electronic schematic was developed using KiCad. An exported version ready for viewing is available directly here:
 **[View the PDF Schematic](pdf/ev_board_v1.0.pdf)**

### Circuit Preview
<p align="center">
  <img src="pics/Board_top_flat.png" width="50%">
</p>

---

## 💡 Example

*(Add your usage examples, code, or application notes for the SLG46826 here)*

---

## 🔗 Useful Links & Documentation

* **Official Datasheet:** Find all detailed technical and electrical specifications of the circuit on the [Renesas SLG46826 Product Page and Datasheet](https://www.renesas.com/en/products/slg46824).
* **Design Software:** The circuit was routed using tools from the [KiCad E.D.A.](https://kicad.org) suite.

---

## ⚖️ Licence

This hardware project is open hardware. The design of this printed circuit board is published under the following licence:

**CERN Open Hardware Licence Version 2 - Strongly Reciprocal (CERN-OHL-S-2.0)**.

You are free to reproduce, modify, and distribute this board, provided that you maintain the same open-sharing conditions for your own modifications (strong reciprocity).

---
© 2026 Olivier DENIZOT - delco-fr.com | Open Hardware
