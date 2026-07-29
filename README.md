# Carnet Balkans

Carnet de voyage web (page unique) : **Bosnie → Serbie → Hongrie**, 1 → 18 août 2026, sans voiture.

Site live : https://lou-theo.github.io/carnet-balkans/

Site statique : un seul fichier `index.html` (HTML + CSS + JS inline). Seule dépendance externe : la carte interactive charge Leaflet + les tuiles CARTO/OpenStreetMap depuis un CDN. Publié via GitHub Pages.

## Deux versions, deux usages

Ce dépôt ne porte que la **version publique**, faite pour être partagée : l'itinéraire, la carte, ce qu'il y a à voir et ce qu'on y mange. Elle s'arrête volontairement aux grandes lignes.

Le **dossier d'organisation complet** (références de réservation, codes, montants, soldes à régler sur place, numéros à appeler, options de repli) est tenu à part, hors du dépôt, et n'est pas publié. Toute information de ce type qui apparaîtrait ici serait à retirer.

## Plan (1 → 18 août 2026)

Axe sud → nord, 17 nuits :

- **Mostar** 🇧🇦 (3 n), entrée par vol direct Paris (Beauvais) → Sarajevo + train/bus ~2 h.
- **Sarajevo** 🇧🇦 (3 n).
- **Belgrade** 🇷🇸 (3 n).
- **Budapest + Hongrie** 🇭🇺 (8 n), base Budapest 10-15 (**Sziget** : une seule journée, le 11, sur un festival qui court du 11 au 15) + escapade détente **Eger + Egerszalók** 15-17 + retour Budapest 17-18.
- Sortie par Budapest le 18.

Hébergement : **les 17 nuits sont réservées** (Mostar, Sarajevo, Belgrade, Budapest, Eger).

Zones à distinguer : **Hongrie = UE + Schengen** (CNI seule, roaming FR, CEAM valable) ; **Bosnie · Serbie = hors UE** (passeport conseillé, forfait téléphone dédié, assurance dédiée). Plus de transit par la Croatie : entrée par vol direct Sarajevo.

Les jours de base à Budapest restent ouverts à des day-trips (Szentendre, coude du Danube) ; rien à réserver.

Pistes explorées puis écartées (Monténégro, Pologne/Cracovie, Tatras…) : archivées dans `PISTES-ABANDONNEES.md`.

## Modifier

Éditer `index.html`, commit, push. GitHub Pages redéploie automatiquement.

## Publier (GitHub Pages)

Settings → Pages → Source : `Deploy from a branch` → branche `main`, dossier `/ (root)`.
URL : `https://<user>.github.io/carnet-balkans/`.
