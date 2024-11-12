---
layout: layouts/page.njk
title: INGRES
eleventyNavigation:
  key: INGRES
  parent:
  order: 4
---

# Présentation
**INGRES** (INstrument de Gestion des REférentielS RH) est une application qui s’adresse aux gestionnaires RH des ministères, aux directions et aux équipes projets des ministères. Les référentiels disponibles (Noyau RH FPE) dans cet outil contribuent à la qualité, la conformité et l’homogénéité des données utilisées. Il met à disposition des **référentiels communs** et facilite les échanges entre les ministères et l’ensemble de la chaîne RH.

Le CISIRH en assure l’hébergement, l’exploitation, l'enrichissement et la maintenance. Il propose également des formations à l’outil.

[Flyer de présentation de INGRES](/files/flyer_ingres.pdf)

# Fonctionnalités
**INGRES** est une base de connaissances conforme à la réglementation RH et un outil de référence pour alimenter les SIRH ministériels. Il permet de :

- **Disposer de tout le contenu du Noyau RH FPE**;
- **Consulter une base documentaire fiable et à jour de la réglementation** relative au classement statutaire de l’agent (les Référentiels de Classification Centraux);
- **Accéder à la totalité du référentiel de paye** : consultation dans un même outil des fiches des référentiels de paye des ministères, des textes juridiques et des barèmes réglementaires afférents, ainsi que des modalités de liquidation des indemnités dans l’application PAYSAGE;
- **Extraire des rapports** utiles au suivi et à la validation du contenu des référentiels;
- Intégrer des flux permettant une **mise à jour automatisée des référentiels SIRH**;
- Une **aide en ligne** et des sessions de formation régulières permettant un accès facilité à l’application et son contenu.
<br>
<br>

**API INGRES** : 2 API "Nomenclatures" et "Diffusion" basées sur les référentiels de l’outil Ingres sont référencées sur le catalogue de la DINUM : https://api.gouv.fr. Ces API ont pour objectif de fluidifier la diffusion et l’utilisation des nomenclatures réglementaires RH de la FPE.

La première **API « Nomenclatures »** permet d’obtenir, au format JSON (JavaScript Objet Notation), via une simple requête, la liste des codes réglementaires de toutes les nomenclatures gérées dans INGRES. Elle peut être utilisée directement dans le développement de vos applications utilisant ces données afin de disposer de référentiels toujours « à jour ». 

La  seconde **API « Diffusions »** permet de récupérer au format Excel ou XML la liste des codes réglementaires présents dans INGRES (dans le même format que celui des diffusions officielles du « Noyau RH FPE »).
