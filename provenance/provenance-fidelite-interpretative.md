# Provenance : fidélité interprétative et fidélité de reconstruction

**Statut :** dossier de provenance public et délimité  
**Date du dossier :** 2026-11-20  
**Auteur :** Gautier Dorval  
**English version:** [Interpretive fidelity provenance](interpretive-fidelity-provenance.md)

## Objet

Ce dossier rassemble les traces qui datent deux éléments du corpus de Gautier Dorval : la définition de la fidélité interprétative et l’emploi de l’expression « fidélité de reconstruction ». Il précise la nature de chaque date, ce que chaque trace établit et ce qu’elle n’établit pas.

Ce dossier attribue et documente. L’auteur est la source de ces traces : le dossier ne constitue pas une validation indépendante du concept, de sa définition ni d’un résultat qui l’emploie.

## Accès aux sources

Le dépôt source du site gautierdorval.com, `GautierDorval/gautierdorval-site`, est privé. Ses révisions sont citées ci-dessous comme identifiants, avec la mention « dépôt source privé » : un lecteur public ne peut pas les consulter. Les extraits nécessaires à la lecture sont reproduits dans ce dossier. Les empreintes indiquées sont les identifiants Git des fichiers (blobs) à la révision citée.

## Nature des dates

| Type de date | Ce qu’elle indique | Ce qu’elle n’établit pas |
|---|---|---|
| Date éditoriale | Valeur inscrite par l’auteur dans les métadonnées du contenu (`date`, `updated`) | La date de mise en ligne ou la date d’un passage précis |
| Date Git | Date déclarée dans un commit | Une publication : une date Git est déclarative |
| Trace d’un service tiers | Enregistrement émis par l’intégration de l’hébergeur | Les octets servis sur le domaine canonique |
| Observation de contenu servi | Récupération datée et conservée du contenu publié | Aucune observation de ce type n’est citée dans ce dossier |

## Traces

### 1. Article contenant l’expression, révision du 21 mars 2026

- **Contenu :** article « Quand un site est bien référencé mais mal compris par les IA », [permalien](https://gautierdorval.com/blogue/phenomenes-interpretation/bien-reference-mal-compris/).
- **Chemin :** `src/content/blog/fr/bien-reference-mal-compris.md`.
- **Révision :** commit `fb3537991d494aade730855874737be041f873dc` (dépôt source privé), date Git 2026-03-21T12:10:36-04:00. Cette révision ajoute le chemin au dépôt.
- **Empreinte du fichier :** `3880e0b27472fe3c00a64f7cec7b494b3e92657b`.
- **Dates éditoriales à cette révision :** `date: '2026-01-22'` et `updated: '2026-03-08'`.
- **Extrait :** « La performance ne se mesure plus uniquement par la visibilité, mais par la fidélité de reconstruction. »
- **Ce que la trace établit :** l’expression figure dans cette révision de l’article.
- **Limites :** les dates éditoriales de janvier et de mars ne datent pas ce passage. La date Git ne prouve pas la mise en ligne de l’article à cette date.

### 2. Définition de fidélité interprétative, révision du 9 mai 2026

- **Contenu :** [définition française](https://gautierdorval.com/definitions/fidelite-interpretative/) et [définition anglaise](https://gautierdorval.com/en/definitions/interpretive-fidelity/).
- **Chemins :** `src/content/definitions/fr/fidelite-interpretative.md` et `src/content/definitions/en/interpretive-fidelity.md`.
- **Révision :** commit `4d67c3a6737c1a941de7069cbd7b9fa063561995` (dépôt source privé), date Git 2026-05-09T10:33:21-04:00. C’est la plus ancienne révision retrouvée pour ces deux chemins.
- **Empreintes des fichiers :** `55dc9d4607884c6b1353b99a387057e3dc15a7a1` (français) et `1995b73dc7aeacbf8a5a82f0669538230eba3e4d` (anglais).
- **Dates éditoriales à cette révision :** `date` et `updated` au 2026-05-09, `stabilizationDate: '2026-05-09'`, `conceptVersion: '1.0'`.
- **Extrait :** « La fidélité interprétative est le degré auquel une sortie préserve le sens canonique, les frontières, l’autorité, les exclusions, la preuve et les conditions de réponse de la source qu’elle prétend représenter. »
- **Ce que la trace établit :** la définition, avec ces éléments, figure à ces chemins dans cette révision.
- **Limites :** la trace ne date ni la première apparition du concept dans tous les supports, ni sa publication initiale. L’expression « fidélité de reconstruction » ne figure pas dans la définition à cette révision.

### 3. Contrôle de déploiement Cloudflare Pages du 9 mai 2026

- **Identifiant :** contrôle 75161687867, dans le registre des contrôles GitHub du dépôt source privé.
- **Émetteur :** application `cloudflare-workers-and-pages`, contrôle nommé « Cloudflare Pages ».
- **Révision liée :** `4d67c3a6737c1a941de7069cbd7b9fa063561995`, la même que la trace 2.
- **Résultat rapporté :** conclusion `success`, titre « Deployed successfully », achèvement le 2026-05-09T14:34:24Z.
- **Lecture :** par l’API GitHub, avec l’accès du propriétaire du dépôt, le 2026-11-20.
- **Article à la même révision :** l’article de la trace 1 contient le même extrait (empreinte `4ded93a131ebc47ec1aa65be94c2e991f365ae33`).
- **Ce que la trace établit :** l’intégration de l’hébergeur rapporte un déploiement réussi de cette révision à cette date.
- **Limites :** un contrôle de déploiement n’atteste pas les octets servis sur le domaine canonique à cette date. Le contrôle indique une URL d’aperçu propre à l’hébergeur ; une telle URL n’est pas une archive permanente et son contenu n’a pas été récupéré pour ce dossier. Une tentative de récupération faite pendant l’audit du 2026-11-20 a échoué ; cet échec ne démontre ni une suppression ni une réponse 404.

### 4. Déclaration terminologique du 20 novembre 2026

- La relation explicite entre « fidélité de reconstruction » et « fidélité interprétative » fait l’objet d’une déclaration terminologique datée du 2026-11-20. Elle est consignée dans la [note terminologique](https://github.com/GautierDorval/interpretive-governance-manifest/blob/main/concepts/fidelite-de-reconstruction.md) du dépôt public du manifeste ; la date de publication de cette note relève de l’historique Git de ce dépôt.
- Cette déclaration n’est pas antidatée. Les traces 1 à 3 montrent un emploi de l’expression et une définition antérieurs, pas une déclaration de relation antérieure.

## Portée linguistique

L’occurrence ancrée par la trace 1 est l’expression française, dans un article français. Ce dossier ne date pas le premier emploi de l’expression anglaise « reconstruction fidelity ».

## Archives tierces

Ce dossier ne cite aucune capture d’archive tierce, par exemple de la Wayback Machine ou de Common Crawl. La recherche de telles captures n’a pas été menée pour cette version du dossier. L’absence de capture citée ne démontre ni leur absence ni leur existence.

## Conclusion strictement soutenue

- L’expression « fidélité de reconstruction » figure dans une révision de l’article datée par Git du 21 mars 2026.
- La définition de fidélité interprétative figure à ses chemins actuels dans une révision datée par Git du 9 mai 2026, et l’intégration de l’hébergeur rapporte un déploiement réussi de cette révision le même jour.
- La relation terminologique explicite est déclarée le 20 novembre 2026.
- Ces traces n’établissent ni le contenu servi à une date passée, ni la première apparition des expressions, ni une validation indépendante.
