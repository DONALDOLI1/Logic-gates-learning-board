<div align="center">

# Logic Gates Learning Board V1.0

**OLITECH · Carte pédagogique d'électronique numérique**

![Project stage](https://img.shields.io/badge/Project-Design%20stage-orange)
![CAD](https://img.shields.io/badge/CAD-KiCad-blue)
![Languages](https://img.shields.io/badge/README-FR%20%7C%20EN-informational)

*Learn digital logic by experimenting with fundamental logic gates.*

</div>

---

**Brand / Marque:** OLITECH  
**Designer / Concepteur:** OLI OLI DONALD  
**Country / Pays:** Cameroon / Cameroun  
**Design software / Logiciel de conception:** KiCad  
**Contact:** [oliolidonald186@gmail.com](mailto:oliolidonald186@gmail.com)

## Table of contents

- [Français](#-français)
  - [Présentation](#présentation)
  - [Objectifs pédagogiques](#objectifs-pédagogiques)
  - [Portes logiques étudiées](#portes-logiques-étudiées)
  - [Circuits intégrés identifiés](#circuits-intégrés-identifiés)
  - [Organisation matérielle](#organisation-matérielle)
  - [Galerie du projet](#galerie-du-projet)
  - [Documents techniques](#documents-techniques)
  - [État et limites du projet](#état-et-limites-du-projet)
- [English](#-english)
  - [Overview](#overview)
  - [Learning objectives](#learning-objectives)
  - [Logic gates covered](#logic-gates-covered)
  - [Identified integrated circuits](#identified-integrated-circuits)
  - [Hardware organization](#hardware-organization)
  - [Project gallery](#project-gallery)
  - [Technical documents](#technical-documents)
  - [Project status and limitations](#project-status-and-limitations)
- [Contact](#contact)

---

## 🇫🇷 Français

### Présentation

**Logic Gates Learning Board V1.0** est une carte électronique pédagogique conçue sous **KiCad** pour faciliter l'apprentissage et l'expérimentation des portes logiques fondamentales.

Le projet vise à offrir aux étudiants et aux passionnés d'électronique une plateforme pratique pour découvrir les fonctions logiques, observer leurs comportements et renforcer les notions d'électronique numérique.

### Objectifs pédagogiques

- Découvrir les fonctions des principales portes logiques.
- Comprendre les relations entre les entrées logiques et les sorties.
- Expérimenter les fonctions combinatoires de base.
- Faire le lien entre les notions théoriques et la conception électronique.

### Portes logiques étudiées

| Porte logique | Fonction |
|---|---|
| NOT (NON) | Inversion logique |
| BUFFER (tampon) | Reproduction de l'état logique |
| AND (ET) | Sortie active si toutes les entrées sont actives |
| OR (OU) | Sortie active si au moins une entrée est active |
| NAND (NON-ET) | Inverse de la fonction AND |
| NOR (NON-OU) | Inverse de la fonction OR |
| XOR (OU exclusif) | Sortie active si les entrées sont différentes |
| XNOR (NON-OU exclusif) | Sortie active si les entrées sont identiques |

### Circuits intégrés et composants principaux

La carte utilise quatre circuits intégrés CMOS : **CD4011 (NAND), CD4071 (OR), CD4081 (AND) et CD4070 (XOR)**. Les fonctions NOT, BUFFER, NOR et XNOR sont également prévues sur le panneau pédagogique.

Les autres composants principaux comprennent un commutateur DIP à 10 positions, des LED de visualisation, des résistances, des condensateurs et des connecteurs. L'alimentation est repérée **VCC / +5 V et GND** sur le schéma.

### Organisation matérielle

La carte regroupe les huit fonctions logiques dans des zones distinctes. Le commutateur DIP permet de configurer les entrées et les LED de visualiser les états logiques.

Le PCB est conçu avec deux faces de cuivre (TOP et BOTTOM) et comporte quatre trous de fixation. Le panneau porte l'identité OLITECH, la mention « Made in Cameroon » et le slogan « Learn – Understand – Undertake ».
### Galerie du projet

Les images suivantes présentent différentes vues de la conception réalisée sous KiCad. Elles illustrent le travail de conception et de visualisation du PCB ; elles ne représentent pas une carte physiquement fabriquée.

| Vue | Aperçu |
|---|---|
| Vue de conception 1 | ![Vue de conception 1](images/BANC%20DIDACTIQUE%20A%20PORTES%20LOGIQUES%20PANEL%201-2.jpg) |
| Vue de conception 2 | ![Vue de conception 2](images/BANC%20DIDACTIQUE%20A%20PORTES%20LOGIQUES%20PANEL-2.jpg) |
| Vue de conception 3 | ![Vue de conception 3](images/BANC%20DIDACTIQUE%20A%20PORTES%20LOGIQUES%20PANEL-2.png) |
| Vue de conception 4 | ![Vue de conception 4](images/banc%20didactique%20%C3%A0%20portes%20logiques%201-2.jpg) |
| Vue de conception 5 | ![Vue de conception 5](images/banc%20didactique%20%C3%A0%20portes%20logiques-2.jpg) |
| Vue de conception 6 | ![Vue de conception 6](images/banc%20didactique%20%C3%A0%20portes%20logiques-2.png) |

### Documents techniques

Les documents suivants complètent la présentation de la carte et permettent de consulter les principaux éléments de conception :

| Document | Description |
|---|---|
| [Côté composants (PDF)](documents/COTE%20COMPOSANT%20BANC%20DIDACTIQUE%20A%20PORTES%20LOGIQUES.pdf) | Vue de la face composants du circuit imprimé |
| [Schéma électronique (PDF)](documents/SCHEMATIC%20BANC%20DIDACTIQUE%20A%20PORTES%20LOGIQUES.pdf) | Schéma électrique de la carte |
| [Typon – Bottom Copper (PDF)](documents/TYPON%20BOTTOM%20COPER%20BANC%20DIDACTIQUE%20A%20PORTES%20LOGIQUES.pdf) | Dessin de la couche cuivre inférieure |
| [Typon – Top Copper (PDF)](documents/TYPON%20TOP%20COPPER%20BANC%20DIDACTIQUE%20A%20PORTES%20LOGIQUES.pdf) | Dessin de la couche cuivre supérieure |

### État et limites du projet

| Élément | État |
|---|---|
| Conception électronique | Réalisée |
| Routage du circuit imprimé (PCB) | Réalisé |
| Visualisation 3D sous KiCad | Réalisée |
| Fabrication physique | Non réalisée |
| Essais sur prototype physique | À effectuer |

> **Important :** le projet est actuellement au stade de conception numérique. La carte n'a pas encore été fabriquée ni testée physiquement. Les images de la galerie montrent la conception KiCad et ses visualisations, et non un prototype fabriqué.

### Fichiers du projet

Les fichiers sources KiCad (schéma et circuit imprimé) ne sont volontairement pas publiés dans ce dépôt.

---

## 🇬🇧 English

### Overview

**Logic Gates Learning Board V1.0** is an educational electronic board designed in **KiCad** to support learning and experimentation with fundamental logic gates.

The project aims to provide students and electronics enthusiasts with a practical platform to explore logic functions, observe their behavior, and strengthen their understanding of digital electronics.

### Learning objectives

- Discover the functions of the main logic gates.
- Understand the relationship between logic inputs and outputs.
- Experiment with basic combinational logic functions.
- Connect theoretical concepts with electronic design.

### Logic gates covered

| Logic gate | Function |
|---|---|
| NOT | Logical inversion |
| BUFFER | Repeats the input logic state |
| AND | Output is active when all inputs are active |
| OR | Output is active when at least one input is active |
| NAND | Inverse of the AND function |
| NOR | Inverse of the OR function |
| XOR | Output is active when inputs differ |
| XNOR | Output is active when inputs are identical |

### Main integrated circuits and components

The board uses four CMOS integrated circuits: **CD4011 (NAND), CD4071 (OR), CD4081 (AND) and CD4070 (XOR)**. The NOT, BUFFER, NOR and XNOR functions are also included on the educational panel.

Other main components include a 10-position DIP switch, indicator LEDs, resistors, capacitors and connectors. The schematic identifies the power connections as **VCC / +5 V and GND**.

### Hardware organization

The board groups the eight logic functions into separate sections. The DIP switch configures the inputs, while LEDs display the logic states.

The PCB is designed with two copper sides (TOP and BOTTOM) and has four mounting holes. The panel displays the OLITECH identity, the “Made in Cameroon” mark and the “Learn – Understand – Undertake” slogan.
### Project gallery

The following images show different views of the KiCad design. They document the PCB design and visualization process; they do not show a physically manufactured board.

| View | Preview |
|---|---|
| Design view 1 | ![Design view 1](images/BANC%20DIDACTIQUE%20A%20PORTES%20LOGIQUES%20PANEL%201-2.jpg) |
| Design view 2 | ![Design view 2](images/BANC%20DIDACTIQUE%20A%20PORTES%20LOGIQUES%20PANEL-2.jpg) |
| Design view 3 | ![Design view 3](images/BANC%20DIDACTIQUE%20A%20PORTES%20LOGIQUES%20PANEL-2.png) |
| Design view 4 | ![Design view 4](images/banc%20didactique%20%C3%A0%20portes%20logiques%201-2.jpg) |
| Design view 5 | ![Design view 5](images/banc%20didactique%20%C3%A0%20portes%20logiques-2.jpg) |
| Design view 6 | ![Design view 6](images/banc%20didactique%20%C3%A0%20portes%20logiques-2.png) |

### Technical documents

The following files provide additional design information and allow the main board documentation to be consulted:

| Document | Description |
|---|---|
| [Component-side view (PDF)](documents/COTE%20COMPOSANT%20BANC%20DIDACTIQUE%20A%20PORTES%20LOGIQUES.pdf) | Component-side view of the PCB |
| [Electronic schematic (PDF)](documents/SCHEMATIC%20BANC%20DIDACTIQUE%20A%20PORTES%20LOGIQUES.pdf) | Board electrical schematic |
| [Bottom Copper artwork (PDF)](documents/TYPON%20BOTTOM%20COPER%20BANC%20DIDACTIQUE%20A%20PORTES%20LOGIQUES.pdf) | Bottom copper-layer artwork |
| [Top Copper artwork (PDF)](documents/TYPON%20TOP%20COPPER%20BANC%20DIDACTIQUE%20A%20PORTES%20LOGIQUES.pdf) | Top copper-layer artwork |

### Project status and limitations

| Item | Status |
|---|---|
| Electronic design | Completed |
| PCB layout and routing | Completed |
| KiCad 3D visualization | Completed |
| Physical manufacturing | Not completed |
| Physical prototype testing | Pending |

> **Important:** this project is currently at the digital design stage. The board has not yet been manufactured or physically tested. The gallery images show the KiCad design and its visualizations, not a manufactured prototype.

### Project files

The KiCad source files (schematic and PCB layout) are intentionally not published in this repository.

---

## Contact

**OLI OLI DONALD · OLITECH**  
Cameroon  
Email: [oliolidonald186@gmail.com](mailto:oliolidonald186@gmail.com)

*OLITECH — Learning digital electronics through practice.*
