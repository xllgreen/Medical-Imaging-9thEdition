# Imagerie Médicale — 9ᵉ Édition
<div align="center">

> *« Guide d'imagerie médicale du XXIᵉ siècle »*

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Claude Code](https://img.shields.io/badge/Claude%20Code-Skill-blueviolet)](https://claude.ai/code)
[![Skills](https://img.shields.io/badge/skills.sh-Compatible-green)](https://skills.sh)

<br>
> Un manuel de compétences cliniques basé sur la 9ᵉ édition d'*Imagerie Médicale* de la People's Medical Publishing House — 136 compétences cliniques essentielles
<br>
<br>
<img src="/assets/Medical Imaging-9thEdition.jpg" width="260px">
<br>

Pourquoi peiner à lire tout un livre ?<br>
Posez une question et obtenez automatiquement la solution tirée du manuel.

<br>

**Autres langues / Other Languages:**

[English](README_EN.md) · [日本語](README_JP.md) · [Français](README_FR.md) · [Русский](README_RU.md)

</div>

---

## Présentation du projet

Ce projet intègre de manière systématique les domaines fondamentaux du diagnostic par imagerie médicale, de la radiologie interventionnelle, de l'analyse assistée par IA et de la sélection des techniques d'imagerie multimodale, couvrant **136 compétences cliniques essentielles** réparties en **13 grandes catégories**.

**Public cible** : Radiologues, cliniciens de toutes spécialités, étudiants en médecine, équipes de radiologie interventionnelle, formateurs en médecine

**Manuel de référence** : *Imagerie Médicale*, 9ᵉ édition, People's Medical Publishing House (manuel du « 14ᵉ Plan quinquennal » de la Commission nationale de la Santé)

**⚠️ Risque ⚠️** : Cette compétence fournit des conseils sur des diagnostics médicaux, traitements, soins d'urgence et procédures invasives à haut risque, qui pourraient être utilisés à tort comme un avis clinique indépendant.

**Mesure d'atténuation** : Utilisez toutes les sorties uniquement comme documents de référence éducatifs ou destinés à être révisés par un clinicien. Une supervision clinique qualifiée, les directives officielles en vigueur, les protocoles locaux et un examen par un expert sont requis avant tout diagnostic, traitement, triage d'urgence ou procédure.

**⚠️ Risque ⚠️** : Les invites ou exemples d'imagerie médicale peuvent impliquer des informations sur les patients ou des métadonnées d'image.

**Mesure d'atténuation** : Sauf autorisation de votre organisation et données correctement anonymisées, évitez de saisir des informations identifiables sur les patients ou des métadonnées d'image.

## Structure du projet

```
Medical-Imaging-9thEdition/
├── SKILL.md              # Configuration centrale — registre des 136 compétences
├── README.md             # Ce document — description du projet et guide d'utilisation
├── <skill-name>/         # Définitions détaillées de chaque compétence
│   └── SKILL.md          #   Détails de la compétence (indications, étapes, précautions)
├── scripts/              # Scripts d'outils exécutables
├── config/               # Fichiers de configuration
├── tests/                # Validation et tests
└── assets/               # Ressources statiques (images, etc.)
```

## Aperçu des catégories de compétences

| Catégorie | Nb comp. | Description |
|-----------|----------|-------------|
| 🏗️ Fondamentaux & Technologies d'imagerie | 9 | Principes des rayons X, CT, IRM, échographie, post-traitement et paramètres de sécurité |
| 🤖 IA & Ressources numériques | 5 | Analyse d'images assistée par IA, flux de travail intelligents, ressources numériques des manuels |
| 📚 Développement de manuels & programmes | 3 | Révision de manuels, principes de révision, stratégies de réforme des programmes cliniques |
| 🧠 Système nerveux central | 7 | Stratégies CT/IRM pour traumatismes crâniens, interprétation IRM médullaire, maladies démyélinisantes et modifications dégénératives |
| 👁️ Tête & Cou | 4 | Diagnostic CT/IRM et différenciation des lésions orbitaires, parotidiennes et mandibulaires |
| 🫁 Thorax & Cardiovasculaire | 18 | Évaluation par imagerie des lésions pulmonaires, pleurales, médiastinales et des pathologies cardiaques et vasculaires |
| 🫄 Sein & Gynécologie | 8 | Mammographie/échographie, tumeurs ovariennes, classification du placenta praevia, embolisation de l'artère utérine |
| 🫃 Système digestif | 19 | Diagnostic et différenciation multimodaux des pathologies gastro-intestinales, hépatobiliaires, pancréatiques et spléniques |
| 🫘 Urinaire & Surrénales | 8 | Tumeurs rénales, classification des lésions kystiques, lithiase urinaire, diagnostic des lésions surrénaliennes |
| 🦴 Système musculo-squelettique | 10 | Classification des fractures et évaluation de la consolidation, tumeurs osseuses, ostéomyélite, pathologies articulaires |
| 👶 Pédiatrie & Maladies congénitales | 4 | Classification NRDS, mesure DDH, réduction d'invagination intestinale, stadification du rachitisme |
| 💉 Radiologie interventionnelle | 19 | Accès vasculaire, embolisation, pose de stent, ablation, TIPS et gestion des complications |
| 📋 Principes diagnostiques complets & Flux de travail | 14 | Raisonnement diagnostique en imagerie, interprétation de comptes rendus, demande d'examen et fusion multimodale |

## Guide de démarrage rapide

### Installation

CLI :
```bash
openclaw skills install medical-imaging-9th-edition
```

Invite :
```bash
Avant d'installer quoi que ce soit, inspectez les métadonnées et les exigences de configuration de la compétence ClawHub.
Si la compétence vous demande d'installer un package ou un CLI tiers, vérifiez sa source, son mainteneur et le contenu du package avant d'exécuter la commande d'installation.
N'installez la compétence "Medical Imaging 9th Edition" (xllgreen/medical-imaging-9th-edition) depuis ClawHub qu'après avoir effectué ces vérifications.
Page de la compétence : https://clawhub.ai/xllgreen/medical-imaging-9th-edition
Limitez votre travail à cette seule compétence.
Après l'installation, aidez-moi à terminer la configuration à partir des métadonnées vérifiées de la compétence.
Utilisez uniquement les métadonnées que vous pouvez vérifier depuis ClawHub ; n'inventez pas d'exigences manquantes.
Demandez avant d'apporter des modifications plus larges à l'environnement.
```

### Utilisation

Chaque compétence se compose de quatre parties :
1. **Quand l'utiliser** — Indications pour déclencher la compétence
2. **Étapes à suivre** — Procédures opératoires standardisées
3. **Précautions** — Contre-indications et avertissements
4. **Références** — Documents complémentaires détaillés

### Stratégies d'interrogation

#### 1. **Recherche conceptuelle**

Question :
```bash
Critères 2019 de la classification des kystes rénaux de Bosniak
```

Réponse :
```bash
## Classification des kystes rénaux de Bosniak (mise à jour 2019)

La classification de Bosniak évalue le risque de malignité des lésions kystiques rénales pour guider les décisions cliniques (surveillance vs. chirurgie).

### Critères de classification

| Classe | Caractéristiques d'imagerie | Risque de malignité | Prise en charge |
|--------|----------------------------|---------------------|-----------------|
| **I** | Kyste simple, paroi fine et lisse, pas de cloison, calcification ou composant solide ; densité hydrique au CT, hypersignal T₂ IRM, pas de rehaussement | <1 % | Bénin, pas de traitement |
| **II** | Quelques (≤3) cloisons fines (≤2 mm) ; fines calcifications possibles ou discret épaississement segmentaire | <5 % | Bénin, pas de traitement |
| **IIF** | Multiples (≥4) cloisons fines ; discret épaississement pariétal/cloisonnaire régulier ; calcifications épaisses et lisses ; pas de tissu mou rehaussé | ~10 % | Surveillance |
| **III** | Un ou plusieurs composants solides avec rehaussement franc ; épaississement pariétal/cloisonnaire irrégulier (≥4 mm) | ~55 % | Résection chirurgicale |
| **IV** | Composant de tissu mou rehaussé (≥25 % de la lésion kystique est solide) | >90 % | Résection chirurgicale |

### Principales mises à jour de 2019
1. **Comptage plus précis des cloisons** : ≤3 = quelques, ≥4 = multiples
2. **Épaisseur pariétale/cloisonnaire quantifiée** : ≤2 mm = fine, ≥4 mm = franchement épaissie
3. **Critères clarifiés pour les « composants de tissu mou rehaussés »**
4. **Recommandation de suivi pour la classe IIF** : premier contrôle à 6–12 mois par CT/IRM, puis extension à tous les 2 ans si stable

> **En résumé** : Les classes I/II sont bénignes — pas de traitement ; la classe IIF nécessite une surveillance régulière ; les classes III/IV nécessitent une résection chirurgicale. Le risque de malignité est fortement corrélé à l'étendue des composants solides.
```

#### 2. **Diagnostic différentiel**

Question :
```bash
Homme de 60 ans, tabagisme chronique. Le CT montre une masse lobulée du lobe supérieur droit avec des spéculations et une adénopathie hilaire homolatérale.
```

Réponse :
```bash
## Analyse du cas

| Élément | Présentation |
|---------|-------------|
| Âge | 60 ans (pic d'incidence du cancer du poumon) |
| Tabagisme | Chronique (facteur de haut risque) |
| Localisation | Lobe supérieur droit |
| Morphologie | Lobulée (évoquant une croissance maligne) |
| Contour | Spéculations (signe de malignité) |
| Signes associés | Adénopathie hilaire homolatérale |

### Diagnostic le plus probable

**Cancer du poumon périphérique (envisager un carcinome épidermoïde ou un adénocarcinome)**

### Arguments diagnostiques
1. **Facteurs de risque cliniques** : 60 ans + tabagisme chronique
2. **Signes d'imagerie malins** : Lobulation, spéculations
3. **Métastases ganglionnaires** : Hypertrophie hilaire homolatérale évoquant un envahissement ganglionnaire régional

### Diagnostics différentiels
- **Tuberculome** : Prédilection pour le segment apical postérieur du lobe supérieur / segment dorsal du lobe inférieur ; lésions satellites, calcifications, rehaussement annulaire possible
- **Pseudotumeur inflammatoire** : Contours relativement lisses ; antécédent infectieux possible
- **Abcès pulmonaire** : Cavitation avec niveau hydro-aérique possible ; début aigu avec signes cliniques d'infection

### Prochaines étapes recommandées
1. CT avec injection pour évaluer la vascularisation lésionnelle et l'état ganglionnaire médiastinal
2. TEP-CT pour un bilan d'extension systémique
3. Biopsie pulmonaire percutanée sous guidage CT pour confirmation histologique
```

#### 3. **Plan de traitement**

Question :
```bash
Patient présentant des nausées, vomissements, douleur sourde de l'hypochondre droit et fièvre après une procédure TACE. Comment prendre en charge ?
```

Réponse :
```bash
## Prise en charge du syndrome post-TACE (chimio-embolisation)

### Évaluation
Les symptômes ci-dessus sont caractéristiques du **syndrome de chimio-embolisation post-TACE (CES)** :
- Nausées, vomissements — réaction gastro-intestinale aux agents chimiothérapeutiques
- Douleur sourde de l'hypochondre droit — ischémie hépatique post-embolisation et réaction inflammatoire
- Fièvre — fièvre d'absorption des tissus nécrotiques (généralement 38–39 °C)

### Plan de prise en charge

| Symptôme | Traitement | Remarques |
|----------|-----------|-----------|
| Fièvre | Antipyrétiques (paracétamol/ibuprofène), refroidissement physique | Si >39 °C persistant, éliminer une infection |
| Douleur | Échelle analgésique à trois paliers de l'OMS | Éviter les AINS chez les patients HCC (risque d'insuffisance hépatique) |
| Nausées/vomissements | Antagonistes des récepteurs 5-HT₃ (ondansétron) | Corriger les déséquilibres hydroélectrolytiques |
| Hépatoprotection | Préparations à base de glycyrrhizine, glutathion réduit | Surveillance postopératoire de la fonction hépatique |

### Complications nécessitant un bilan urgent
- Douleur abdominale sévère et progressivement croissante → éliminer **abcès hépatique / cholécystite / pancréatite**
- Fièvre >39 °C avec frissons → éliminer **complication infectieuse**
- Ascite croissante, ictère aggravé → éliminer **insuffisance hépatique aiguë**

> **Évolution typique** : Le CES dure généralement 3 à 7 jours et se résorbe progressivement avec des soins de soutien symptomatiques. Si les symptômes persistent au-delà de 7 jours ou s'aggravent progressivement, un bilan complémentaire des complications est justifié.
```

## À propos de l'auteur

**Xiaolü (xllgreen)** ([https://xllgreen.github.io](https://xllgreen.github.io)) — Étudiant à l'École de médecine clinique de l'Université de Jiujiang · Passionné de technologie

## Support technique
<br>
Projet PDF2App : https://pdf2app.cn
<br>
Microsoft Visual Studio Code : https://code.visualstudio.com/
<br>
Claude Code for VS Code : https://claude.com/
© 2026 Anthropic PBC
<br>
<br>
<img src="https://cdn.deepseek.com/logo.png?x-image-process=image%2Fresize%2Cw_1920" width="130px">
<br>API DeepSeek : https://platform.deepseek.com/
© 2026 Hangzhou DeepSeek Artificial Intelligence Basic Technology Research Co., Ltd. Tous droits réservés
<br>
<br>
<img src="https://cdn.cnbj1.fds.api.mi-img.com/aife/mimo-blog-fe/doc_build/static/image/logo.99baaffe.png" width="130px">
<br>API Xiaomi Mimo : https://platform.xiaomimimo.com/
Copyright © 2010 – 2026 Xiaomi. All Rights Reserved
<br>

## Licence

Le contenu de ce projet est compilé à partir de la 9ᵉ édition d'*Imagerie Médicale* de la People's Medical Publishing House et est destiné uniquement à des fins d'étude et de référence.

## Star History

<a href="https://www.star-history.com/?repos=xllgreen%2FMedical-Imaging-9thEdition&type=date&legend=top-left">
 <picture>
   <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/chart?repos=xllgreen/Medical-Imaging-9thEdition&type=date&theme=dark&legend=top-left" />
   <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/chart?repos=xllgreen/Medical-Imaging-9thEdition&type=date&legend=top-left" />
   <img alt="Star History Chart" src="https://api.star-history.com/chart?repos=xllgreen/Medical-Imaging-9thEdition&type=date&legend=top-left" />
 </picture>
</a>
