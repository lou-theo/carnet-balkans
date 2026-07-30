# Carnet Balkans

Carnet de voyage web (page unique) : **Bosnie → Serbie → Hongrie**, 1 → 18 août 2026, sans voiture.

Site live : https://lou-theo.github.io/carnet-balkans/

Site statique : un seul fichier `index.html` (HTML + CSS + JS inline). Seule dépendance externe : la carte interactive charge Leaflet + les tuiles CARTO/OpenStreetMap depuis un CDN. Publié via GitHub Pages.

## Trois niveaux, un seul amont

- Le **dossier d'organisation complet** (références de réservation, codes, montants, soldes à régler sur place, numéros à appeler, options de repli) est la **source de vérité**. C'est un **fichier HTML privé**, tenu hors du dépôt dans un dossier Drive dédié dont un fichier de contexte donne le mode d'emploi, et il n'est pas publié. **À charger intégralement avant toute modification de ce dépôt**, sans exception, même pour une retouche qui paraît isolée : en demander l'emplacement s'il n'est pas connu. Il porte le déroulé heure par heure, les arbitrages déjà verrouillés et les faits redressés ; corriger ici sans l'avoir lu, c'est réintroduire une erreur déjà tranchée ou publier un fait que l'amont a démenti.
- Ce dépôt ne porte que la **version publique**, faite pour être partagée : l'itinéraire, la carte, où l'on dort, ce qu'il y a à voir et ce qu'on y mange. Elle s'arrête volontairement aux grandes lignes et **recopie l'amont, jamais l'inverse** : un fait qui change se corrige d'abord dans le dossier complet.
- Les **notes de préparation** (matériel déjà en stock, relevés de prix, sources) vivent dans `temp/`, hors suivi Git. Elles ne gardent que ce qui n'a pas sa place dans le dossier complet.

Toute référence, tout code et tout montant à régler qui apparaîtrait dans ce dépôt serait à retirer.

## Plan (1 → 18 août 2026)

Axe sud → nord, 17 nuits :

- **Mostar** 🇧🇦 (3 n), entrée par vol direct Paris (Beauvais) → Sarajevo + train/bus ~2 h.
- **Sarajevo** 🇧🇦 (3 n).
- **Belgrade** 🇷🇸 (3 n).
- **Budapest + Hongrie** 🇭🇺 (8 n), base Budapest 10-12, escapade détente **Eger + Egerszalók** 12-14, retour Budapest 14-18 (**Sziget** : une seule journée, le 15, la clôture d'un festival qui court du 11 au 15). L'escapade passe avant le festival pour laisser deux jours calmes après, et pour ne rien mettre sur le jour du vol.
- Sortie par Budapest le 18.

Hébergement : **les 17 nuits sont réservées** (Mostar, Sarajevo, Belgrade, Budapest, Eger).

Zones à distinguer : **Hongrie = UE + Schengen** (CNI seule, roaming FR, CEAM valable) ; **Bosnie · Serbie = hors UE** (passeport conseillé, forfait téléphone dédié, assurance dédiée). Plus de transit par la Croatie : entrée par vol direct Sarajevo.

Les jours de base à Budapest restent ouverts à des day-trips (Szentendre, coude du Danube) ; rien à réserver.

Pistes explorées puis écartées (Monténégro, Pologne/Cracovie, Tatras…) : leur détail chiffré est archivé hors du dépôt, avec le dossier complet, qui n'en garde que la décision.

## Modifier

Éditer `index.html`, commit, push. GitHub Pages redéploie automatiquement.

## Publier (GitHub Pages)

Settings → Pages → Source : `Deploy from a branch` → branche `main`, dossier `/ (root)`.
URL : `https://<user>.github.io/carnet-balkans/`.
