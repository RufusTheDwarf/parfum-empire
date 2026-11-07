 <div align="center">

<a id="top"></a>

<img src="https://capsule-render.vercel.app/api?type=waving&height=285&color=0:17251B,18:344735,42:53694C,68:8A7954,86:B28A4D,100:D8C79F&text=PARFUM%20EMPIRE&fontSize=55&fontColor=F6F0E2&fontAlignY=34&desc=THE%20ART%20OF%20BUILDING%20A%20PERFUME%20HOUSE&descSize=14&descAlignY=57&animation=fadeIn" width="100%" alt="Parfum Empire luxury botanical perfume house banner in sage green, forest green and brass"/>

<img src="https://readme-typing-svg.demolab.com?font=Georgia&weight=600&size=19&duration=3200&pause=1000&color=D6B979&center=true&vCenter=true&width=850&height=45&lines=HARVEST+THE+INGREDIENTS.;MASTER+THE+ART+OF+FORMULATION.;BUILD+YOUR+OWN+MANUFACTURE.;CREATE+A+PERFUME+EMPIRE." alt="Animated Parfum Empire tagline"/>

<br>

<img src="https://raw.githubusercontent.com/RufusTheDwarf/parfum-empire/main/public/assets/perfume-emblem.svg" width="112" alt="Original Parfum Empire perfume bottle emblem"/>

<br>

**Cultive ton jardin. Compose tes fragrances. Développe ta maison de parfumerie.**

A 2D browser-based perfume tycoon with exploration, deterministic gathering, handcrafted recipes, automated production and prestige progression.

<br>

[![Game](https://img.shields.io/badge/GENRE-2D_TYCOON-53694C?style=flat)](https://github.com/RufusTheDwarf/parfum-empire)
[![TypeScript](https://img.shields.io/badge/LANGUAGE-TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![Vite](https://img.shields.io/badge/BUILD-Vite_6-646CFF?style=flat&logo=vite&logoColor=white)](https://vite.dev/)
[![Vitest](https://img.shields.io/badge/TESTS-Vitest_3-6E9F18?style=flat)](https://vitest.dev/)
[![Node](https://img.shields.io/badge/RUNTIME-Node.js_22-339933?style=flat&logo=nodedotjs&logoColor=white)](https://nodejs.org/)
[![Canvas](https://img.shields.io/badge/RENDERING-Canvas_2D-8A7954?style=flat)](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API)
[![SVG](https://img.shields.io/badge/ARTWORK-Original_SVG-B28A4D?style=flat)](https://developer.mozilla.org/en-US/docs/Web/SVG)
[![Storage](https://img.shields.io/badge/SAVES-LocalStorage-53694C?style=flat)](https://developer.mozilla.org/en-US/docs/Web/API/Window/localStorage)
[![Web Audio](https://img.shields.io/badge/AUDIO-Web_Audio_API-A55E43?style=flat)](https://developer.mozilla.org/en-US/docs/Web/API/Web_Audio_API)
[![MIT](https://img.shields.io/github/license/RufusTheDwarf/parfum-empire?style=flat&color=2E9D68)](LICENSE)

[![Package](https://img.shields.io/badge/PACKAGE-0.4.0-8A7954?style=flat)](package.json)
[![CI](https://img.shields.io/github/actions/workflow/status/RufusTheDwarf/parfum-empire/ci.yml?branch=main&style=flat&label=CI)](https://github.com/RufusTheDwarf/parfum-empire/actions/workflows/ci.yml)
[![Dev Container](https://img.shields.io/badge/ENVIRONMENT-GitHub_Codespaces-181717?style=flat&logo=github&logoColor=white)](.devcontainer/devcontainer.json)
[![Private Package](https://img.shields.io/badge/NPM_PACKAGE-Private-64748B?style=flat&logo=npm&logoColor=white)](package.json)
[![Responsive](https://img.shields.io/badge/INPUT-Keyboard_+_Touch-0F766E?style=flat)](apps/web/src/workshop-scene.ts)
[![No Backend](https://img.shields.io/badge/ARCHITECTURE-Client_Side-8A7954?style=flat)](docs/ARCHITECTURE.md)

<br>

[![Stars](https://img.shields.io/github/stars/RufusTheDwarf/parfum-empire?style=flat&color=D6B979)](https://github.com/RufusTheDwarf/parfum-empire/stargazers)
[![Forks](https://img.shields.io/github/forks/RufusTheDwarf/parfum-empire?style=flat&color=53694C)](https://github.com/RufusTheDwarf/parfum-empire/forks)
[![Issues](https://img.shields.io/github/issues/RufusTheDwarf/parfum-empire?style=flat&color=A55E43)](https://github.com/RufusTheDwarf/parfum-empire/issues)
[![Last Commit](https://img.shields.io/github/last-commit/RufusTheDwarf/parfum-empire?style=flat&color=B28A4D)](https://github.com/RufusTheDwarf/parfum-empire/commits/main)
[![Repository Size](https://img.shields.io/github/repo-size/RufusTheDwarf/parfum-empire?style=flat&color=8A7954)](https://github.com/RufusTheDwarf/parfum-empire)

<br>

[**Explore the project**](https://github.com/RufusTheDwarf/parfum-empire) · [**Run the game**](#05--installation) · [**Game systems**](#03--gameplay-systems) · [**Architecture**](#07--technical-architecture)

</div>

<p align="center">
<img src="https://capsule-render.vercel.app/api?type=rect&height=6&color=0:344735,30:53694C,65:B28A4D,100:D8C79F" width="100%" alt="Forest green, sage and brass section divider"/>
</p>

<div align="center">

<img src="https://raw.githubusercontent.com/RufusTheDwarf/parfum-empire/main/public/assets/bottle-product.svg" width="125" alt="Original illustrated perfume product bottle"/>
<img src="https://raw.githubusercontent.com/RufusTheDwarf/parfum-empire/main/public/assets/perfume-emblem.svg" width="155" alt="Original Parfum Empire perfume house emblem"/>
<img src="https://raw.githubusercontent.com/RufusTheDwarf/parfum-empire/main/public/assets/bottle-rare.svg" width="125" alt="Original rare perfume bottle illustration"/>

<br>

<sub>ORIGINAL GAME ARTWORK // PARFUM EMPIRE</sub>

</div>

## 01 / Présentation

**Parfum Empire** est un jeu de gestion en 2D jouable dans un navigateur.

Le joueur commence avec un terrain vide et construit progressivement sa propre maison de parfumerie. Il doit récolter des matières botaniques, apprendre à composer des fragrances, fabriquer des flacons, vendre ses créations et développer une manufacture automatisée.

Le jeu combine deux dimensions :

- **L'atelier explorable :** un monde 2D dans lequel le personnage se déplace entre le jardin botanique, le laboratoire, le comptoir et les différents étages.
- **La gestion tycoon :** une économie de production, des machines, des recherches, des commandes clients, plusieurs collections et un système de prestige.

L'objectif est de passer d'un petit atelier artisanal à un empire de parfumerie capable de produire des essences rares.

### Identité visuelle

L'interface adopte une direction artistique inspirée d'une maison de parfumerie traditionnelle :

| Couleur | Utilisation |
|---|---|
| Vert mousse `#344735` | Identité principale |
| Sauge `#53694C` | Nature et botanique |
| Ivoire `#F6F0E2` | Fonds et panneaux |
| Laiton `#B28A4D` | Prestige et détails |
| Cuivre `#A55E43` | Accents et interactions |
| Encre `#292C24` | Texte et contraste |

Le monde et les illustrations utilisent cette palette, avec des variations visuelles selon la collection active.

<p align="center">
<img src="https://capsule-render.vercel.app/api?type=rect&height=4&color=0:B28A4D,50:53694C,100:344735" width="76%" alt="Brass to moss green divider"/>
</p>

## 02 / Vue d'ensemble du jeu

<div align="center">

<img src="https://raw.githubusercontent.com/RufusTheDwarf/parfum-empire/main/public/assets/machine-lab.svg" width="76" alt="Illustration of the perfume laboratory"/>
<img src="https://raw.githubusercontent.com/RufusTheDwarf/parfum-empire/main/public/assets/machine-botanical.svg" width="76" alt="Illustration of botanical production machine"/>
<img src="https://raw.githubusercontent.com/RufusTheDwarf/parfum-empire/main/public/assets/machine-bottling.svg" width="76" alt="Illustration of perfume bottling machine"/>
<img src="https://raw.githubusercontent.com/RufusTheDwarf/parfum-empire/main/public/assets/machine-extractor.svg" width="76" alt="Illustration of essence extractor"/>
<img src="https://raw.githubusercontent.com/RufusTheDwarf/parfum-empire/main/public/assets/machine-luxury.svg" width="76" alt="Illustration of luxury perfume machine"/>

</div>

<grid>

</grid>

| Système | Contenu actuel |
|---|---:|
| Matières botaniques | 7 |
| Recettes de parfum | 5 |
| Équipements de production | 10 |
| Recherches améliorables | 5 |
| Collections / mondes | 3 |
| Étages accessibles | 3 |
| Parcelles botaniques bonus | 3 |
| Rangs de réputation | 10 |
| Durée maximale de production hors ligne | 8 heures |

Ces éléments sont définis dans le moteur économique TypeScript et les systèmes de progression du jeu.

## 03 / Gameplay Systems

### La boucle de jeu

Le gameplay repose sur une progression concrète. Les matières ne sont pas obtenues par des récompenses aléatoires : chaque parcelle du jardin correspond à une ressource précise.

```mermaid
flowchart TD
    A["Acheter le terrain de départ"] --> B["Explorer le jardin botanique"]
    B --> C["Récolter une matière précise"]
    C --> D["Découvrir et choisir une recette"]
    D --> E["Rejoindre le laboratoire"]
    E --> F["Consommer les ingrédients"]
    F --> G["Fabriquer un flacon"]
    G --> H["Rejoindre le comptoir"]
    H --> I["Vendre ou livrer une commande"]
    I --> J["Gagner des pièces et de la réputation"]
    J --> K["Acheter des machines et des recherches"]
    K --> L["Automatiser la manufacture"]
    L --> M["Débloquer de nouveaux étages et mondes"]
    M --> N["Rebirth et ascension"]
    N --> B

    style A fill:#344735,color:#fff,stroke:#B28A4D
    style B fill:#53694C,color:#fff,stroke:#D6B979
    style C fill:#53694C,color:#fff,stroke:#D6B979
    style D fill:#8A7954,color:#fff,stroke:#E2CC99
    style E fill:#8A7954,color:#fff,stroke:#E2CC99
    style G fill:#A55E43,color:#fff,stroke:#E2CC99
    style I fill:#53694C,color:#fff,stroke:#D6B979
    style L fill:#344735,color:#fff,stroke:#B28A4D
    style N fill:#5B4D54,color:#fff,stroke:#B6A4CE
```

### 1. Le terrain et le jardin botanique

Une nouvelle partie commence sur un terrain non développé.

Le joueur doit acheter le terrain de départ pour **1 000 pièces** avant de pouvoir commencer la production artisanale.

Le jardin propose sept matières :

| Matière | Rareté |
|---|---|
| Lavande | Commune |
| Menthe | Commune |
| Pétales de rose | Inhabituelle |
| Bergamote | Inhabituelle |
| Bois de santal | Rare |
| Jasmin | Rare |
| Résine ambrée | Très rare |

Chaque parcelle est associée à une matière déterminée. Le joueur choisit où se rendre et ce qu'il souhaite récolter.

Les interactions utilisent le déplacement du personnage et la proximité des postes. Tenir la touche d'interaction ne déclenche pas une récolte en boucle : l'action est déclenchée sur l'appui initial.

<div align="center">

<img src="https://raw.githubusercontent.com/RufusTheDwarf/parfum-empire/main/public/assets/material-lavender.svg" width="65" alt="Lavender ingredient illustration"/>
<img src="https://raw.githubusercontent.com/RufusTheDwarf/parfum-empire/main/public/assets/material-mint.svg" width="65" alt="Mint ingredient illustration"/>
<img src="https://raw.githubusercontent.com/RufusTheDwarf/parfum-empire/main/public/assets/material-rose.svg" width="65" alt="Rose petals ingredient illustration"/>
<img src="https://raw.githubusercontent.com/RufusTheDwarf/parfum-empire/main/public/assets/material-bergamot.svg" width="65" alt="Bergamot ingredient illustration"/>
<img src="https://raw.githubusercontent.com/RufusTheDwarf/parfum-empire/main/public/assets/material-sandalwood.svg" width="65" alt="Sandalwood ingredient illustration"/>
<img src="https://raw.githubusercontent.com/RufusTheDwarf/parfum-empire/main/public/assets/material-jasmine.svg" width="65" alt="Jasmine ingredient illustration"/>
<img src="https://raw.githubusercontent.com/RufusTheDwarf/parfum-empire/main/public/assets/material-resin.svg" width="65" alt="Amber resin ingredient illustration"/>

<sub>BOTANICAL COLLECTION // SEVEN MATERIALS</sub>

</div>

### 2. Carnet de formulations

Le laboratoire permet de fabriquer cinq parfums.

Chaque recette possède une combinaison d'ingrédients et un prix de vente défini.

| Parfum | Ingrédients nécessaires | Prix de vente de base |
|---|---|---:|
| Brise verte | 1 lavande + 1 menthe | 2 |
| Rose tendre | 1 lavande + 1 rose | 3 |
| Aube citronnée | 1 bergamote + 1 menthe | 4 |
| Bouquet royal | 1 lavande + 1 rose + 1 jasmin | 6 |
| Velours ambré | 1 santal + 1 résine + 1 jasmin | 10 |

Les ingrédients nécessaires sont consommés lors de la formulation.

Le joueur doit donc organiser ses récoltes avant de pouvoir produire les parfums les plus complexes.

Les améliorations de finition peuvent ensuite augmenter la valeur de vente des flacons.

### 3. Fabrication et vente

L'atelier contient plusieurs postes physiques :

- Le jardin botanique pour la récolte.
- Le laboratoire pour composer les parfums.
- Le comptoir pour vendre les flacons.
- Les escaliers pour accéder aux étages supérieurs.

Le joueur doit rejoindre le bon poste pour effectuer l'action.

La vente génère des revenus et contribue à la progression de la maison.

### 4. Commandes clients

Des clients passent commande auprès de la parfumerie.

Le système comprend cinq modèles de commandes déterministes, avec des clients, des maisons et des parfums demandés différents.

Le joueur doit :

1. Consulter la demande active.
2. Préparer le bon parfum.
3. Fabriquer la quantité demandée.
4. Rejoindre le comptoir.
5. Livrer la commande complète.

Une livraison réussie apporte une prime supplémentaire et augmente la réputation de la maison.

La réputation comporte dix rangs, avec une prime de livraison qui progresse de 50 % jusqu'à 95 %.

La quantité demandée augmente progressivement, jusqu'à un maximum de cinq flacons.

### 5. Parcelles bonus

Trois parcelles supplémentaires peuvent être achetées :

| Parcelle | Matière | Prix |
|---|---|---:|
| Seconde parcelle | Lavande | 2 500 |
| Troisième parcelle | Menthe | 25 000 |
| Quatrième parcelle | Rose | 250 000 |

Les parcelles bonus restent invisibles et inaccessibles tant qu'elles n'ont pas été achetées.

Elles permettent d'augmenter progressivement la capacité de récolte du jardin.

<p align="center">
<img src="https://capsule-render.vercel.app/api?type=rect&height=5&color=0:53694C,40:B28A4D,100:A55E43" width="100%" alt="Sage brass copper divider"/>
</p>

## 04 / The Manufacture

La manufacture constitue le cœur de la progression automatisée.

Les équipements permettent de générer une production passive sans devoir effectuer chaque action manuellement.

Il existe dix machines réparties entre les différents étages.

### Catalogue des machines

| Équipement | Étage | Fonction |
|---|---:|---|
| Table de formulation | 0 | Mélange les premières notes parfumées |
| Alambic de cuivre | 0 | Distille des extraits |
| Ligne d'embouteillage | 1 | Remplit et ferme les flacons |
| Atelier de parfumeur | 1 | Produit des compositions premium |
| Extracteur astral | 2 | Synthétise des essences rares |
| Serre botanique | 1 | Cultive des matières premières |
| Presse à enfleurage | 1 | Capture les notes florales |
| Atelier de luxe | 2 | Produit des parfums haut de gamme |
| Distillateur de cristal | 2 | Traite les essences spécialisées |
| Manufacture orbitale | 2 | Équipement industriel avancé |

<div align="center">

<table>
<tr>
<td align="center" width="33%">
<img src="https://raw.githubusercontent.com/RufusTheDwarf/parfum-empire/main/public/assets/machine-formulation.svg" width="85" alt="Formulation table"/>
<br><sub>FORMULATION</sub>
</td>
<td align="center" width="33%">
<img src="https://raw.githubusercontent.com/RufusTheDwarf/parfum-empire/main/public/assets/machine-still.svg" width="85" alt="Copper still"/>
<br><sub>DISTILLATION</sub>
</td>
<td align="center" width="33%">
<img src="https://raw.githubusercontent.com/RufusTheDwarf/parfum-empire/main/public/assets/machine-bottling.svg" width="85" alt="Bottling line"/>
<br><sub>EMBOUTEILLAGE</sub>
</td>
</tr>
<tr>
<td align="center" width="33%">
<img src="https://raw.githubusercontent.com/RufusTheDwarf/parfum-empire/main/public/assets/machine-enfleurage.svg" width="85" alt="Enfleurage press"/>
<br><sub>ENFLEURAGE</sub>
</td>
<td align="center" width="33%">
<img src="https://raw.githubusercontent.com/RufusTheDwarf/parfum-empire/main/public/assets/machine-crystal.svg" width="85" alt="Crystal distiller"/>
<br><sub>CRISTAL</sub>
</td>
<td align="center" width="33%">
<img src="https://raw.githubusercontent.com/RufusTheDwarf/parfum-empire/main/public/assets/machine-orbital.svg" width="85" alt="Orbital manufactory"/>
<br><sub>MANUFACTURE</sub>
</td>
</tr>
</table>

<sub>ORIGINAL PRODUCTION MACHINE ASSETS // PUBLIC/ASSETS</sub>

</div>

### Production economics

Chaque équipement possède :

- Un coût d'achat.
- Un revenu de production.
- Un cycle de production.
- Un emplacement physique.
- Un étage d'installation.
- Un coût d'exploitation.

Les coûts d'exploitation sont déduits des revenus bruts afin de calculer le rendement net.

Le jeu affiche la production nette par seconde, et les revenus hors ligne utilisent également le calcul net.

Cela évite de présenter une machine comme rentable lorsque son entretien dépasse réellement sa production.

### Machines visibles dans le monde

Les équipements achetés ne sont pas seulement des valeurs dans un catalogue.

Ils sont transmis à la scène et dessinés dans l'atelier à des emplacements définis.

Ils disposent d'animations de fonctionnement et d'un compteur de quantité installée.

<p align="center">
<img src="https://capsule-render.vercel.app/api?type=rect&height=4&color=0:A55E43,50:B28A4D,100:53694C" width="75%" alt="Copper brass green divider"/>
</p>

## 05 / Atelier 2D et déplacement

Le jeu utilise une scène 2D dessinée avec **Canvas 2D**.

Le monde est plus grand que la zone visible. La caméra suit le personnage et reste dans les limites de la carte.

Le joueur peut parcourir l'atelier, rejoindre les parcelles, interagir avec les machines et accéder aux différents postes.

### Dimensions de la scène

| Élément | Dimensions |
|---|---:|
| Surface logique de rendu | 960 × 440 |
| Monde de jeu | 1 440 × 720 |
| Rendu | Canvas 2D |
| Caméra | Suivi du personnage |

### Contrôles

| Action | Contrôle |
|---|---|
| Marcher | Flèches directionnelles |
| Marcher | ZQSD |
| Se déplacer vers une position | Clic sur le sol |
| Se déplacer sur mobile | Toucher le sol |
| Récolter ou interagir | E |
| Interagir | Bouton à l'écran |
| Se déplacer sur téléphone | Pavé directionnel tactile |

Le déplacement par clic ou toucher utilise un système de pathfinding A* sur une grille pour contourner les obstacles.

Le système gère notamment :

- Les collisions avec les parcelles.
- Les machines achetées.
- Les murs et les ouvertures.
- Les déplacements diagonaux.
- Les escaliers et les transitions entre étages.
- Le recalcul d'un chemin lorsqu'un déplacement est bloqué.

La scène utilise également :

- Une animation de marche avec orientation.
- Des gestes d'interaction.
- Des plantes animées.
- Des particules lors des actions.
- Des effets visuels adaptés à chaque événement de gameplay.

### Commandes tactiles

Le jeu conserve une prise en charge des petits écrans.

Les commandes tactiles permettent de déplacer le personnage sans dépendre du clavier.

Les contrôles sont adaptés aux actions prolongées et à la gestion des appuis annulés, afin d'éviter des déplacements ou interactions bloqués.

### Effets sonores

Les sons sont générés directement avec la **Web Audio API**.

Ils utilisent des oscillateurs et des fréquences définies dans le code.

Aucun fichier audio externe n'est requis.

Les effets peuvent être désactivés dans les paramètres, et la préférence est conservée localement.

<p align="center">
<img src="https://capsule-render.vercel.app/api?type=rect&height=5&color=0:344735,50:8A7954,100:B28A4D" width="100%" alt="Green brass divider"/>
</p>

## 06 / Étages et collections

La maison de parfumerie dispose de trois étages accessibles progressivement.

Chaque étage possède ses propres équipements et son identité visuelle.

### Les trois étages

| Étage | Nom | Orientation |
|---|---|---|
| 0 | Artisanat | Jardin, laboratoire et comptoir |
| 1 | Manufacture | Lignes de conditionnement et production industrielle |
| 2 | Essences rares | Extraction et équipements spécialisés |

Les étages sont déverrouillés avec des prérequis et un coût.

Les escaliers physiques assurent la montée et la descente. Le sélecteur d'étage permet également de revenir dans les zones déjà ouvertes.

La position de départ après un changement d'étage est calculée près de l'escalier d'arrivée.

Les étages débloqués restent accessibles dans les sauvegardes.

### Les trois collections

Le jeu comprend trois mondes ou collections avec des palettes visuelles différentes.

<div align="center">

<img src="https://raw.githubusercontent.com/RufusTheDwarf/parfum-empire/main/public/assets/material-lavender.svg" width="70" alt="Lavender, first collection"/>
<img src="https://raw.githubusercontent.com/RufusTheDwarf/parfum-empire/main/public/assets/material-resin.svg" width="70" alt="Amber resin, second collection"/>
<img src="https://raw.githubusercontent.com/RufusTheDwarf/parfum-empire/main/public/assets/bottle-rare.svg" width="95" alt="Rare bottle, advanced collection"/>

</div>

| Monde | Thème | Déblocage |
|---|---|---|
| Jardin de Verre | Premières notes fraîches | Disponible dès le début |
| Maison d'Ambre | Bois précieux et vanille noire | 1 rebirth |
| Palais Astral | Essences les plus rares | 3 rebirths |

Chaque monde possède ses propres multiplicateurs de coût et de revenus.

La palette du monde actif est transmise à la scène afin de modifier l'apparence de l'atelier sans changer les règles de collision ou l'économie.

<p align="center">
<img src="https://capsule-render.vercel.app/api?type=rect&height=4&color=0:B28A4D,50:8A7954,100:7D6B91" width="75%" alt="Brass bronze violet divider"/>
</p>

## 07 / Recherches, contrats et prestige

La progression ne repose pas uniquement sur l'achat de machines.

Le bureau regroupe plusieurs systèmes qui permettent de développer la maison.

### Les cinq recherches

| Recherche | Effet |
|---|---|
| Concentré Absolu | Augmente la production des machines de 20 % par niveau |
| Instinct du botaniste | Récolte une matière supplémentaire tous les deux niveaux |
| Contrats verriers | Réduit le prix des équipements de 5 % par niveau |
| Extraction spécialisée | Améliore les récoltes de matières rares |
| Finition de luxe | Augmente la valeur de vente des flacons de 10 % par niveau |

Les recherches possèdent des coûts évolutifs et un niveau maximum de dix.

### Contrats et honneurs

Les objectifs du jeu récompensent notamment :

- L'installation des premiers équipements.
- Le développement de la manufacture.
- Les ventes cumulées.
- L'exploration de nouveaux mondes.
- La progression vers l'empire complet.

Les contrats et honneurs sont gérés par le moteur économique et leurs états sont conservés dans la sauvegarde.

### Rebirth

Le rebirth permet de recommencer une progression tout en conservant un bonus permanent.

Il sert notamment à déverrouiller les collections suivantes.

### Ascension totale

L'ascension totale constitue une progression supérieure au rebirth classique.

Elle permet d'obtenir des **Essences originelles**.

Les valeurs principales définies dans le moteur sont :

| Paramètre | Valeur |
|---|---:|
| Valeur de prestige de base | 1 000 000 |
| Bonus de production par essence | +75 % |
| Premier niveau requis pour l'ascension totale | 10 |

Les essences augmentent durablement la production et permettent de recommencer avec un avantage permanent.

<p align="center">
<img src="https://capsule-render.vercel.app/api?type=rect&height=5&color=0:53694C,45:B28A4D,100:A55E43" width="100%" alt="Sage brass copper divider"/>
</p>

## 08 / Sauvegarde et progression hors ligne

La progression est conservée localement dans le navigateur.

Le système de sauvegarde comprend plusieurs protections pour réduire les risques de perte accidentelle.

### Sauvegarde locale

Les données sont stockées dans `localStorage`.

Le système conserve notamment :

- La trésorerie.
- Les matières récoltées.
- Les flacons fabriqués.
- Les machines achetées.
- Les recherches.
- Les commandes livrées.
- La réputation.
- Les étages déverrouillés.
- Les collections débloquées.
- Les rebirths et l'ascension.
- La date de dernière sauvegarde.

### Copie de secours

Avant de remplacer la sauvegarde principale, le jeu actualise une copie de secours.

Au démarrage :

1. Le jeu valide la sauvegarde principale.
2. Si elle est illisible, il essaie la copie de secours.
3. Il peut également récupérer une ancienne sauvegarde.
4. Si toutes les données sont invalides, il crée une nouvelle partie et affiche un avertissement.

### Import et export JSON

Le joueur peut :

- Exporter sa sauvegarde dans un fichier JSON.
- Copier les données de sauvegarde.
- Importer un fichier JSON.
- Importer des données depuis une autre partie.
- Récupérer certaines anciennes sauvegardes grâce à la migration.

### Production hors ligne

La production passive continue à être calculée lorsque le joueur revient sur sa partie.

La durée maximale prise en compte est limitée à **8 heures**.

Le rendement hors ligne utilise la production nette après entretien des machines.

Le système traite également le retour sur un onglet qui était resté en arrière-plan.

<badge color="warning">Limite importante</badge>

La sauvegarde reste locale au navigateur. Elle n'est pas synchronisée entre plusieurs appareils et peut être modifiée par le joueur.

<p align="center">
<img src="https://capsule-render.vercel.app/api?type=rect&height=4&color=0:344735,50:B28A4D,100:D6B979" width="75%" alt="Green brass gold divider"/>
</p>

## 09 / Architecture technique

Le projet sépare les règles économiques, la scène 2D et l'interface.

Cette séparation permet de modifier les règles du jeu sans devoir réécrire le rendu graphique.

### Architecture générale

```mermaid
flowchart TB
    USER["Player"]
    BROWSER["Browser"]

    subgraph FRONTEND["Parfum Empire Web Application"]
        MAIN["main.ts<br/>Interface and game state"]
        ECONOMY["economy.ts<br/>Game rules and progression"]
        SCENE["workshop-scene.ts<br/>Canvas 2D and navigation"]
        CSS["style.css<br/>Responsive interface"]
        ASSETS["public/assets<br/>SVG illustrations"]
    end

    STORAGE["LocalStorage<br/>Main save + backup"]
    AUDIO["Web Audio API"]

    USER --> BROWSER
    BROWSER --> MAIN
    MAIN --> ECONOMY
    MAIN --> SCENE
    MAIN --> CSS
    SCENE --> ASSETS
    MAIN --> STORAGE
    MAIN --> AUDIO

    style USER fill:#344735,color:#fff,stroke:#B28A4D
    style BROWSER fill:#53694C,color:#fff,stroke:#D6B979
    style MAIN fill:#344735,color:#fff,stroke:#D6B979
    style ECONOMY fill:#53694C,color:#fff,stroke:#D6B979
    style SCENE fill:#8A7954,color:#fff,stroke:#E2CC99
    style CSS fill:#A55E43,color:#fff,stroke:#E2CC99
    style ASSETS fill:#53694C,color:#fff,stroke:#B28A4D
    style STORAGE fill:#5B4D54,color:#fff,stroke:#B6A4CE
    style AUDIO fill:#795D48,color:#fff,stroke:#E2CC99
```

### Responsabilités des modules

| Fichier | Responsabilité |
|---|---|
| `apps/web/src/main.ts` | Interface, état du jeu, progression, événements et sauvegardes |
| `apps/web/src/economy.ts` | Récolte, recettes, ventes, production, commandes, recherches et prestige |
| `apps/web/src/workshop-scene.ts` | Monde 2D, caméra, déplacement, pathfinding, collisions, animations et interactions |
| `apps/web/src/style.css` | Interface, présentation responsive et commandes tactiles |
| `public/assets/*.svg` | Illustrations des matières, flacons et machines |
| `tests/economy.test.ts` | Vérification du moteur économique |
| `tests/workshop-scene.test.ts` | Vérification de la scène, des collisions et des déplacements |

### Séparation des responsabilités

**`economy.ts`**

Le moteur économique ne dépend pas du DOM ou du Canvas.

Il contient les fonctions qui déterminent les règles et les résultats des actions du joueur.

**`workshop-scene.ts`**

La scène gère le monde et les interactions physiques. Elle informe l'application lorsqu'un poste est utilisé au lieu de modifier directement l'argent ou l'inventaire.

**`main.ts`**

Le module principal connecte la scène aux règles économiques, actualise l'interface et gère les sauvegardes.

### Technologies

<div align="center">

<img src="https://skillicons.dev/icons?i=typescript,vite,nodejs,html,css,git,github&theme=light" alt="TypeScript, Vite, Node.js, HTML, CSS, Git and GitHub technology icons"/>

<br>

[![TypeScript](https://img.shields.io/badge/TypeScript-~5.8.3-3178C6?style=flat&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![Vite](https://img.shields.io/badge/Vite-^6.3.5-646CFF?style=flat&logo=vite&logoColor=white)](https://vite.dev/)
[![Vitest](https://img.shields.io/badge/Vitest-^3.2.4-6E9F18?style=flat)](https://vitest.dev/)
[![Node.js](https://img.shields.io/badge/Node.js-22-339933?style=flat&logo=nodedotjs&logoColor=white)](https://nodejs.org/)

</div>

| Technologie | Utilisation |
|---|---|
| TypeScript | Logique du jeu et typage |
| Vite | Serveur de développement et compilation |
| Vitest | Tests automatisés |
| HTML | Structure de l'application |
| CSS | Interface responsive |
| Canvas 2D | Rendu du monde et des personnages |
| SVG | Illustrations des produits et équipements |
| LocalStorage | Sauvegarde locale |
| Web Audio API | Effets sonores générés localement |
| GitHub Actions | Tests et vérification continue |

Le jeu ne dépend actuellement pas de Phaser. La scène 2D est gérée par le module Canvas personnalisé.

<p align="center">
<img src="https://capsule-render.vercel.app/api?type=rect&height=5&color=0:B28A4D,50:53694C,100:344735" width="100%" alt="Brass to forest green divider"/>
</p>

## 10 / Installation

### Prérequis

| Outil | Version |
|---|---|
| Node.js | 22.12 ou supérieur |
| npm | Version fournie avec Node.js |
| Navigateur | Navigateur moderne compatible avec Canvas et Web Audio |

Le dépôt utilise Node.js 22 dans son environnement GitHub Actions et son Dev Container.

### Cloner le projet

```bash
git clone https://github.com/RufusTheDwarf/parfum-empire.git

cd parfum-empire
```

### Installer les dépendances

```bash
npm install
```

### Lancer le serveur de développement

```bash
npm run dev
```

Vite démarre sur le port `5173`.

Ouvre l'adresse affichée dans le terminal, généralement :

```text
http://localhost:5173
```

Le serveur de développement est configuré pour écouter sur `0.0.0.0`, ce qui permet également de l'utiliser dans GitHub Codespaces.

### GitHub Codespaces

Le dépôt contient un Dev Container basé sur Node.js 22.

Il configure :

- L'installation automatique des dépendances.
- Le transfert du port `5173`.
- L'ouverture du navigateur lorsque le port est détecté.

Pour commencer dans Codespaces, ouvre le dépôt, crée un environnement Codespace sur `main` et laisse la commande de création installer les dépendances.

### Compilation de production

```bash
npm run build
```

Cette commande lance d'abord le contrôle TypeScript, puis génère les fichiers de production avec Vite.

Le résultat est placé dans :

```text
dist/
```

Les fichiers générés peuvent être servis par un hébergement statique compatible.

Aucun serveur backend n'est nécessaire pour la version actuelle du jeu.

<p align="center">
<img src="https://capsule-render.vercel.app/api?type=rect&height=4&color=0:53694C,50:8A7954,100:B28A4D" width="75%" alt="Sage bronze brass divider"/>
</p>

## 11 / Tests et intégration continue

Le projet utilise **Vitest** pour vérifier les règles économiques et les comportements de la scène.

### Tests existants

| Fichier | Cas de test déclarés |
|---|---:|
| `tests/economy.test.ts` | 35 |
| `tests/workshop-scene.test.ts` | 25 |
| **Total** | **60** |

Les tests économiques couvrent notamment :

- La création d'une nouvelle partie.
- La validation et la migration des sauvegardes.
- La récolte et le stock de matières.
- La fabrication des recettes.
- Les ventes et les commandes clients.
- La production et les coûts d'exploitation.
- Les recherches et les améliorations.
- Les déblocages d'étages et de mondes.
- Les rebirths et l'ascension.
- Le calcul de la progression hors ligne.

Les tests de scène couvrent notamment :

- Les conditions de déblocage du terrain.
- Les interactions au clavier.
- Les collisions.
- Les passages dans les murs.
- Les déplacements et chemins.
- Les positions de transition entre étages.
- Les profils d'effets visuels.

### Exécuter les tests

```bash
npm test
```

### Vérification TypeScript

```bash
npm run typecheck
```

### Build complet

```bash
npm run build
```

### GitHub Actions

Le workflow `CI` est configuré pour s'exécuter sur les pushes vers `main` et les Pull Requests ciblant `main`.

Il effectue les opérations suivantes :

1. Récupération du dépôt.
2. Installation de Node.js 22.
3. Installation des dépendances.
4. Vérification TypeScript.
5. Exécution des tests Vitest.
6. Compilation de production.

[Voir les exécutions GitHub Actions](https://github.com/RufusTheDwarf/parfum-empire/actions/workflows/ci.yml).

<badge color="info">Automation</badge> Le dépôt contient également un workflow de nettoyage des branches fusionnées. Il supprime les branches de Pull Request déjà fusionnées dans le dépôt, tout en conservant la branche par défaut et celles associées à des Pull Requests encore ouvertes.

Ce workflow nécessite des permissions GitHub d'écriture sur les contenus du dépôt.

<p align="center">
<img src="https://capsule-render.vercel.app/api?type=rect&height=5&color=0:344735,50:B28A4D,100:A55E43" width="100%" alt="Forest brass copper divider"/>
</p>

## 12 / Sauvegardes, sécurité et limites

Parfum Empire est actuellement une application côté navigateur.

Il n'existe pas de backend distant ni de système de comptes utilisateurs.

### Ce qui est déjà disponible

- Sauvegarde locale.
- Copie de secours.
- Récupération d'une sauvegarde principale illisible.
- Import et export JSON.
- Migration de formats de sauvegarde historiques.
- Validation de données.
- Production hors ligne plafonnée à huit heures.

### Ce qui n'est pas encore implémenté

| Fonctionnalité | État |
|---|---|
| Comptes utilisateurs | Non implémentés |
| Sauvegardes cloud | Non implémentées |
| Synchronisation entre appareils | Non implémentée |
| Multijoueur | Non implémenté |
| Backend de jeu | Non implémenté |
| Validation économique côté serveur | Non implémentée |
| Protection anti-triche serveur | Non implémentée |
| Version 3D | Non implémentée |

### Sécurité côté client

Les fichiers JavaScript livrés au navigateur peuvent être inspectés par les joueurs.

La sauvegarde locale peut également être modifiée volontairement.

Le système valide certaines données malformées et restaure des copies de secours, mais cela ne constitue pas une protection anti-triche complète.

Pour sécuriser réellement l'argent, l'inventaire et la progression, une future version en ligne devra déplacer les données faisant autorité vers un backend capable de valider les opérations.

Le renommage ou l'obfuscation des fichiers côté navigateur ne constitue pas une solution de sécurité.

<p align="center">
<img src="https://capsule-render.vercel.app/api?type=rect&height=4&color=0:B28A4D,50:53694C,100:344735" width="75%" alt="Brass green divider"/>
</p>

## 13 / Structure du dépôt

Voici l'arborescence réelle de la branche `main`.

```text
parfum-empire/
│
├── .devcontainer/
│   └── devcontainer.json
│
├── .github/
│   └── workflows/
│       ├── ci.yml
│       └── cleanup-merged-branches.yml
│
├── apps/
│   └── web/
│       ├── src/
│       │   ├── economy.ts
│       │   ├── main.ts
│       │   ├── style.css
│       │   └── workshop-scene.ts
│       │
│       └── tsconfig.json
│
├── docs/
│   ├── ARCHITECTURE.md
│   ├── IMPLEMENTATION_STATUS.md
│   ├── PLATFORM_DECISION.md
│   ├── RESEARCH.md
│   └── ROADMAP.md
│
├── public/
│   └── assets/
│       ├── bottle-product.svg
│       ├── bottle-rare.svg
│       ├── perfume-emblem.svg
│       ├── material-bergamot.svg
│       ├── material-jasmine.svg
│       ├── material-lavender.svg
│       ├── material-mint.svg
│       ├── material-resin.svg
│       ├── material-rose.svg
│       ├── material-sandalwood.svg
│       ├── material-unknown.svg
│       ├── machine-botanical.svg
│       ├── machine-bottling.svg
│       ├── machine-crystal.svg
│       ├── machine-enfleurage.svg
│       ├── machine-extractor.svg
│       ├── machine-formulation.svg
│       ├── machine-lab.svg
│       ├── machine-luxury.svg
│       ├── machine-orbital.svg
│       └── machine-still.svg
│
├── tests/
│   ├── economy.test.ts
│   ├── workshop-scene.test.ts
│   └── tsconfig.json
│
├── .editorconfig
├── .env.example
├── .gitignore
├── AGENTS.md
├── CHANGELOG.md
├── CONTRIBUTING.md
├── index.html
├── LICENSE
├── package.json
└── tsconfig.json
```

### Documentation du projet

| Document | Contenu |
|---|---|
| [AGENTS.md](AGENTS.md) | Carte technique et règles pour les assistants de développement |
| [CHANGELOG.md](CHANGELOG.md) | Historique des évolutions |
| [CONTRIBUTING.md](CONTRIBUTING.md) | Règles de contribution |
| [ARCHITECTURE.md](docs/ARCHITECTURE.md) | Organisation des modules |
| [IMPLEMENTATION_STATUS.md](docs/IMPLEMENTATION_STATUS.md) | État des systèmes |
| [PLATFORM_DECISION.md](docs/PLATFORM_DECISION.md) | Choix de plateforme |
| [RESEARCH.md](docs/RESEARCH.md) | Recherche technique initiale |
| [ROADMAP.md](docs/ROADMAP.md) | Feuille de route |

<p align="center">
<img src="https://capsule-render.vercel.app/api?type=rect&height=5&color=0:53694C,40:B28A4D,100:8A7954" width="100%" alt="Sage brass bronze divider"/>
</p>

## 14 / Feuille de route

Le projet dispose déjà d'une base jouable avec une économie, un atelier explorable, des machines, plusieurs étages et une progression persistante.

Les prochaines améliorations concernent notamment :

- La validation visuelle de l'atelier sur différents navigateurs.
- Les déplacements et collisions sur téléphone.
- L'équilibrage à long terme des coûts et de la production.
- Le rythme de progression des commandes clients.
- L'amélioration de la présentation des différentes collections.
- Les tests sur une session de jeu prolongée.
- L'évaluation d'un backend si des comptes ou des sauvegardes cloud deviennent nécessaires.

La feuille de route complète est disponible dans [docs/ROADMAP.md](docs/ROADMAP.md).

<p align="center">
<img src="https://capsule-render.vercel.app/api?type=rect&height=4&color=0:A55E43,50:B28A4D,100:53694C" width="75%" alt="Copper brass sage divider"/>
</p>

## 15 / Contribution

Les améliorations, corrections et propositions sont les bienvenues.

Le projet suit quelques principes importants :

1. Les règles économiques doivent rester dans `economy.ts`.
2. La scène ne doit pas modifier directement l'argent ou l'inventaire.
3. Les modifications des règles de jeu doivent être accompagnées de tests déterministes.
4. Le jeu doit rester utilisable au clavier et sur écran tactile.
5. Les données sensibles ne doivent jamais être versionnées.
6. Les changements importants doivent passer les commandes de vérification.

### Contribuer

```bash
git switch -c feature/my-improvement

git add .

git diff --cached --check

npm run typecheck
npm test
npm run build

git commit -S -m "feat: describe the improvement"

git push origin feature/my-improvement
```

Voir [CONTRIBUTING.md](CONTRIBUTING.md) pour les règles détaillées.

<p align="center">
<img src="https://capsule-render.vercel.app/api?type=rect&height=4&color=0:344735,50:B28A4D,100:D6B979" width="75%" alt="Green brass gold divider"/>
</p>

## 16 / Licence

Le projet est distribué sous la **licence MIT**.

Le fichier [LICENSE](LICENSE) contient le texte complet.

Copyright (c) 2026 Rufus.

---

## Remerciements et crédits

Parfum Empire s'appuie sur des outils open source et des technologies web maintenues par leurs communautés.

### Technologies

- [**TypeScript**](https://www.typescriptlang.org/) pour le typage et la logique du jeu.
- [**Vite**](https://vite.dev/) pour le serveur de développement et la compilation.
- [**Vitest**](https://vitest.dev/) pour les tests automatisés.
- [**Node.js**](https://nodejs.org/) pour l'environnement d'exécution et les outils de développement.
- [**GitHub Actions**](https://github.com/features/actions) pour l'intégration continue.
- [**MDN Web Docs**](https://developer.mozilla.org/) pour les références des API Web, notamment Canvas, LocalStorage et Web Audio.

### Ressources de présentation

- [**Capsule Render**](https://github.com/kyechan99/capsule-render) pour les bannières et séparateurs SVG.
- [**Readme Typing SVG**](https://github.com/DenverCoder1/readme-typing-svg) pour le texte animé.
- [**Skill Icons**](https://github.com/tandpfun/skill-icons) pour les logos des technologies.
- [**Shields.io**](https://shields.io/) pour les badges.

### Illustrations du jeu

Les illustrations des flacons, matières botaniques, machines et emblèmes sont des ressources SVG intégrées au dépôt dans `public/assets/`.

Elles font partie de l'identité visuelle de Parfum Empire et sont utilisées directement par l'application.

Merci aux mainteneurs des outils open source, aux développeurs des technologies web et à toutes les personnes qui contribuent à rendre ce projet possible.

<div align="center">

<img src="https://raw.githubusercontent.com/RufusTheDwarf/parfum-empire/main/public/assets/perfume-emblem.svg" width="100" alt="Parfum Empire perfume house emblem"/>

## PARFUM EMPIRE

**Une maison se construit note après note.**

<br>

### Créé et maintenu par

# [RufusTheDwarf](https://github.com/RufusTheDwarf)

[![GitHub](https://img.shields.io/badge/CREATOR-RUFUSTHEDWARF-181717?style=flat&logo=github&logoColor=white)](https://github.com/RufusTheDwarf)
[![Project](https://img.shields.io/badge/PROJECT-PARFUM_EMPIRE-53694C?style=flat&logo=git&logoColor=white)](https://github.com/RufusTheDwarf/parfum-empire)
[![MIT](https://img.shields.io/badge/LICENSE-MIT-2E9D68?style=flat)](LICENSE)
[![TypeScript](https://img.shields.io/badge/BUILT_WITH-TYPESCRIPT-3178C6?style=flat&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![Vite](https://img.shields.io/badge/POWERED_BY-VITE-646CFF?style=flat&logo=vite&logoColor=white)](https://vite.dev/)
[![Vitest](https://img.shields.io/badge/TESTED_WITH-VITEST-6E9F18?style=flat)](https://vitest.dev/)

<br>

[![Star the Project](https://img.shields.io/badge/STAR_THIS_PROJECT-D6B979?style=flat&logo=github&logoColor=292C24)](https://github.com/RufusTheDwarf/parfum-empire/stargazers)
[![Report an Issue](https://img.shields.io/badge/REPORT_AN_ISSUE-A55E43?style=flat&logo=github&logoColor=white)](https://github.com/RufusTheDwarf/parfum-empire/issues)
[![Explore the Source](https://img.shields.io/badge/EXPLORE_THE_SOURCE-344735?style=flat&logo=github&logoColor=white)](https://github.com/RufusTheDwarf/parfum-empire)

<br>

<img src="https://raw.githubusercontent.com/RufusTheDwarf/parfum-empire/main/public/assets/bottle-product.svg" width="78" alt="Parfum Empire product bottle"/>
<img src="https://raw.githubusercontent.com/RufusTheDwarf/parfum-empire/main/public/assets/material-rose.svg" width="63" alt="Rose ingredient"/>
<img src="https://raw.githubusercontent.com/RufusTheDwarf/parfum-empire/main/public/assets/material-lavender.svg" width="63" alt="Lavender ingredient"/>
<img src="https://raw.githubusercontent.com/RufusTheDwarf/parfum-empire/main/public/assets/bottle-rare.svg" width="78" alt="Rare perfume bottle"/>

<br>

**HARVEST. FORMULATE. PRODUCE. ASCEND.**

<sub>Designed and maintained by RufusTheDwarf · MIT License · © 2026</sub>

<br>

<img src="https://readme-typing-svg.demolab.com?font=Georgia&weight=600&size=17&duration=3200&pause=1000&color=B28A4D&center=true&vCenter=true&width=700&height=38&lines=YOUR+HOUSE.+YOUR+FORMULAS.;YOUR+EMPIRE+STARTS+HERE.;ONE+MORE+FRAGRANCE..." alt="Animated Parfum Empire footer tagline"/>

<img src="https://capsule-render.vercel.app/api?type=waving&height=165&color=0:17251B,18:344735,42:53694C,68:8A7954,86:B28A4D,100:D8C79F&section=footer" width="100%" alt="Centered Parfum Empire footer banner in forest green, sage and brass"/>

</div>
