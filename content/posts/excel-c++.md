---
Weight: 100
title: "Générer des fichiers Excel en C++"
date: 2021-05-07T17:24:06+02:00
draft: false
cover: /img/budget.jpg
author: SD
avatar: me/sd.png
tags:
 - C++
categories:
 - Informatique
---
Pour générer un fichier XLSX en C++ (sans nécessité d'avoir les produits offices installés), il existe plusieurs bibliothèques disponibles. Il est parfois difficile de s'y retrouver car nombres de bibliothèques s'avèrent n'être plus maintenues.

<!--more-->
Voici une petite sélection : 

- <a href="https://libxlsxwriter.github.io/index.html">libxlsxwriter</a> : bibliothèque en C, simple à utiliser, très bien documentée et avec peu de dépendances.
- <a href="https://github.com/troldal/OpenXLSX">openxlsx</a> : simple à utiliser, permet aussi de lire et manipuler des fichiers Excel.
- <a href="https://github.com/tfussell/xlnt">xlnt</a> : même démarche de la bibliothèque précédente.
- <a href="https://github.com/dbzhang800/QtXlsxWriter">qtxlswriter</a> :  simple a utilisée, elle est basée sur la bibliothèque Qt (Qtlib - est-ce encore du C++ ?)
- <a href="https://www.libxl.com/">libxl</a> : très complète, peut être utilisée pour lire et modifier des fichiers xlsx mais aussi xls. Pb : c'est la seule bibliothèque présentée ici qui n'est pas open-source. Elle nécessite en outre l'achat d'une licence dont le prix est de l'ordre de 200$ par développeur et par environnement (Windows, Linux, Ios, ...) - existe en version C, C++, C# et Delphi

Il serait intéressant aussi de voir quels outils utilise libre-office (écrit en C++) pour manipuler les fichier Excel...
Photo de Shopify Partners provenant de Burst


