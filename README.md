# Carnet Balkans

Carnet de voyage web (page unique) — **Bosnie → Serbie → Hongrie**, 1 → 18 août 2026, sans voiture.

Site live : https://lou-theo.github.io/carnet-balkans/

Site statique : un seul fichier `index.html` (HTML + CSS + JS inline). Seule dépendance externe : la carte interactive charge Leaflet + les tuiles CARTO/OpenStreetMap depuis un CDN. Publié via GitHub Pages.

## Plan (1 → 18 août 2026)

Axe sud → nord, 17 nuits :

- **Mostar** 🇧🇦 (3 n) — entrée par vol direct Paris (Beauvais) → Sarajevo + train/bus ~2 h.
- **Sarajevo** 🇧🇦 (3 n).
- **Belgrade** 🇷🇸 (3 n).
- **Budapest + Hongrie** 🇭🇺 (8 n) — base Budapest 10-15 (**Sziget** : une seule journée, le 11, sur un festival qui court du 11 au 15) + escapade détente **Eger + Egerszalók** 15-17 + retour Budapest 17-18.
- Sortie par Budapest le 18.

Hébergement : **Mostar, Budapest et Eger réservés** ; **Sarajevo et Belgrade restent à réserver**.

Zones à distinguer : **Hongrie = UE + Schengen** (CNI seule, roaming FR, CEAM valable) ; **Bosnie · Serbie = hors UE** (passeport conseillé, eSIM, assurance dédiée). Plus de transit par la Croatie : entrée par vol direct Sarajevo.

Escapade hongroise calée : **Eger + thermes d'Egerszalók** (15-17 août). Jours de base Budapest ouverts à des day-trips (Szentendre, coude du Danube).

Pistes explorées puis écartées (Monténégro, Pologne/Cracovie, Tatras…) : archivées dans `PISTES-ABANDONNEES.md`.

## Modifier

Éditer `index.html`, commit, push. GitHub Pages redéploie automatiquement.

## Budget (17 nuits, profil routard/auberges)

Auberges/dortoirs partout, sauf l'étape repos d'Eger (hôtel-spa en demi-pension).

**Déjà payé — ≈ 930 €**

| Poste | Montant |
|---|---|
| Vols A/R directs (Beauvais→Sarajevo, Budapest→Beauvais) | ≈ 311 € |
| Hébergement réservé : Mostar 3 n, Budapest 5 + 1 n, Eger 2 n | ≈ 468 € |
| Sziget, billet journée du 11 | 105 € |
| Assurance voyage Heymondo (~16 j) | ≈ 44 € |

**Reste à prévoir — ≈ 660–1 040 €**

| Poste | Estimation |
|---|---|
| Hébergement Sarajevo + Belgrade (3 n chacun, dortoir) | 100–150 € |
| Transferts terrestres (train Sarajevo↔Mostar, bus Sarajevo→Belgrade→Budapest) | 55–90 € |
| Repas & boissons (2 dîners et 2 petits-déjeuners déjà inclus à Eger) | 300–480 € |
| Activités (tour Herzégovine 50 €, thermes Széchenyi et Egerszalók, tours depuis Sarajevo) | 190–290 € |
| eSIM Bosnie/Serbie, 10 Go | 15–25 € |

**Total du voyage : ≈ 1 590–1 970 €.** Les estimations restantes sont des ordres de grandeur en pleine saison d'août.

## Publier (GitHub Pages)

Settings → Pages → Source : `Deploy from a branch` → branche `main`, dossier `/ (root)`.
URL : `https://<user>.github.io/carnet-balkans/`.
