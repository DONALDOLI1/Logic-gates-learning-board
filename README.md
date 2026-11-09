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

### Circuits intégrés identifiés

Le schéma électronique et la face composants identifient quatre circuits intégrés de la famille logique CMOS :

| Référence | Fonction représentée |
|---|---|
| CD4011 | Portes NAND |
| CD4071 | Portes OR |
| CD4081 | Portes AND |
| CD4070 | Portes XOR |

Les fonctions NOT, BUFFER, NOR et XNOR figurent également sur le panneau pédagogique. Les documents fournis ne permettent pas d'établir à eux seuls le détail complet de leur réalisation interne ni de confirmer une nomenclature exhaustive de fabrication.

### Organisation matérielle

La face composants présente une organisation pédagogique en blocs :

- **Entrées logiques :** un commutateur DIP à 10 positions permet de configurer les états d'entrée.
- **Zones de manipulation :** les fonctions NOT, BUFFER, AND, OR, NAND, NOR, XOR et XNOR sont repérées et séparées sur la carte.
- **Visualisation :** des LED associées à des résistances permettent d'observer les états logiques, avec une LED dédiée à l'indication d'alimentation.
- **Alimentation :** le dessin identifie les connexions VCC et GND ainsi qu'un condensateur repéré C5.
- **Circuits intégrés :** les emplacements U1 à U4 sont associés aux références CD4071, CD4070, CD4011 et CD4081.

Le panneau porte également l'identité OLITECH, la mention « Made in Cameroon » et le slogan « Learn – Understand – Undertake ».

### Circuit imprimé

Les typons TOP COPPER et BOTTOM COPPER documentent les deux faces de cuivre du PCB. Les dessins montrent le cheminement des pistes, les pastilles de composants et quatre trous de fixation situés aux coins de la carte. La présence de ces deux typons documente un routage sur deux faces ; elle ne constitue pas une preuve de fabrication physique.
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

### Identified integrated circuits

The schematic and component-side drawing identify four CMOS logic integrated circuits:

| Part number | Function shown |
|---|---|
| CD4011 | NAND gates |
| CD4071 | OR gates |
| CD4081 | AND gates |
| CD4070 | XOR gates |

The NOT, BUFFER, NOR and XNOR functions are also displayed on the educational panel. The supplied documents alone do not establish their complete internal implementation or confirm an exhaustive manufacturing bill of materials.

### Hardware organization

The component-side drawing shows the board arranged into educational sections:

- **Logic inputs:** a 10-position DIP switch is provided to configure input states.
- **Experiment areas:** NOT, BUFFER, AND, OR, NAND, NOR, XOR and XNOR functions are individually labelled.
- **Visual feedback:** LEDs with associated resistors allow logic states to be observed, with a dedicated power-indicator LED.
- **Power:** VCC and GND connections are identified, together with a capacitor marked C5.
- **Integrated circuits:** footprints U1 to U4 are associated with the CD4071, CD4070, CD4011 and CD4081 references.

The panel also displays the OLITECH identity, the “Made in Cameroon” mark and the “Learn – Understand – Undertake” slogan.

### Printed circuit board

The TOP COPPER and BOTTOM COPPER artwork documents both copper sides of the PCB. The drawings show track routing, component pads and four mounting holes located at the board corners. These two artwork files document a two-sided routing design; they do not prove that the board has been physically manufactured.
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
