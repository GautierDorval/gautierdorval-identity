# Provenance: interpretive fidelity and reconstruction fidelity

**Status:** bounded public provenance record  
**Record date:** 2026-11-20  
**Author:** Gautier Dorval  
**Version française :** [Provenance de la fidélité interprétative](provenance-fidelite-interpretative.md)

## Purpose

This record gathers the traces that date two elements of Gautier Dorval's corpus: the definition of interpretive fidelity and the use of the French expression "fidélité de reconstruction" (reconstruction fidelity). It states the nature of each date, what each trace establishes and what it does not establish.

This record attributes and documents. The author is the source of these traces: the record is not an independent validation of the concept, its definition or any result that uses it.

## Access to sources

The source repository of the gautierdorval.com site, `GautierDorval/gautierdorval-site`, is private. Its revisions are cited below as identifiers, marked "private source repository": a public reader cannot consult them. The excerpts needed to read this record are reproduced here. The fingerprints given are the Git identifiers of the files (blobs) at the cited revision.

## Nature of the dates

| Type of date | What it indicates | What it does not establish |
|---|---|---|
| Editorial date | Value entered by the author in the content metadata (`date`, `updated`) | The date of publication online or the date of a specific passage |
| Git date | Date declared in a commit | A publication: a Git date is declarative |
| Third-party service trace | Record issued by the hosting provider's integration | The bytes served on the canonical domain |
| Observation of served content | Dated and retained retrieval of the published content | No observation of this kind is cited in this record |

## Traces

### 1. Article containing the expression, revision of 21 March 2026

- **Content:** French article "Quand un site est bien référencé mais mal compris par les IA", [permalink](https://gautierdorval.com/blogue/phenomenes-interpretation/bien-reference-mal-compris/).
- **Path:** `src/content/blog/fr/bien-reference-mal-compris.md`.
- **Revision:** commit `fb3537991d494aade730855874737be041f873dc` (private source repository), Git date 2026-03-21T12:10:36-04:00. This revision adds the path to the repository.
- **File fingerprint:** `3880e0b27472fe3c00a64f7cec7b494b3e92657b`.
- **Editorial dates at this revision:** `date: '2026-01-22'` and `updated: '2026-03-08'`.
- **Excerpt (French):** "La performance ne se mesure plus uniquement par la visibilité, mais par la fidélité de reconstruction." (Performance is no longer measured only by visibility, but by reconstruction fidelity.)
- **What the trace establishes:** the expression appears in this revision of the article.
- **Limits:** the January and March editorial dates do not date this passage. The Git date does not prove that the article was online on that date.

### 2. Interpretive fidelity definition, revision of 9 May 2026

- **Content:** [English definition](https://gautierdorval.com/en/definitions/interpretive-fidelity/) and [French definition](https://gautierdorval.com/definitions/fidelite-interpretative/).
- **Paths:** `src/content/definitions/en/interpretive-fidelity.md` and `src/content/definitions/fr/fidelite-interpretative.md`.
- **Revision:** commit `4d67c3a6737c1a941de7069cbd7b9fa063561995` (private source repository), Git date 2026-05-09T10:33:21-04:00. It is the oldest revision found for both paths.
- **File fingerprints:** `1995b73dc7aeacbf8a5a82f0669538230eba3e4d` (English) and `55dc9d4607884c6b1353b99a387057e3dc15a7a1` (French).
- **Editorial dates at this revision:** `date` and `updated` set to 2026-05-09, `stabilizationDate: '2026-05-09'`, `conceptVersion: '1.0'`.
- **Excerpt:** "Interpretive fidelity is the degree to which an output preserves the canonical meaning, boundaries, authority, exclusions, evidence and response conditions of the source it claims to represent."
- **What the trace establishes:** the definition, with these elements, appears at these paths in this revision.
- **Limits:** the trace dates neither the first appearance of the concept in every medium nor its initial publication. The expression "fidélité de reconstruction" does not appear in the definition at this revision.

### 3. Cloudflare Pages deployment check of 9 May 2026

- **Identifier:** check 75161687867, in the GitHub check records of the private source repository.
- **Issuer:** `cloudflare-workers-and-pages` application, check named "Cloudflare Pages".
- **Linked revision:** `4d67c3a6737c1a941de7069cbd7b9fa063561995`, the same as trace 2.
- **Reported result:** conclusion `success`, title "Deployed successfully", completed at 2026-05-09T14:34:24Z.
- **Reading:** through the GitHub API, with the repository owner's access, on 2026-11-20.
- **Article at the same revision:** the article of trace 1 contains the same excerpt (fingerprint `4ded93a131ebc47ec1aa65be94c2e991f365ae33`).
- **What the trace establishes:** the hosting provider's integration reports a successful deployment of this revision on that date.
- **Limits:** a deployment check does not attest the bytes served on the canonical domain on that date. The check gives a preview URL specific to the hosting provider; such a URL is not a permanent archive, and its content was not retrieved for this record. A retrieval attempt made during the audit of 2026-11-20 failed; that failure demonstrates neither a deletion nor a 404 response.

### 4. Terminological declaration of 20 November 2026

- The explicit relationship between reconstruction fidelity and interpretive fidelity is the subject of a terminological declaration dated 2026-11-20. It is recorded in the [terminology note](https://github.com/GautierDorval/interpretive-governance-manifest/blob/main/concepts/reconstruction-fidelity.md) of the public manifest repository; the publication date of that note is a matter of that repository's Git history.
- This declaration is not backdated. Traces 1 to 3 show an earlier use of the expression and an earlier definition, not an earlier declaration of the relationship.

## Language scope

The occurrence anchored by trace 1 is the French expression, in a French article. This record does not date the first use of the English expression reconstruction fidelity.

## Third-party archives

This record cites no third-party archive capture, for example from the Wayback Machine or Common Crawl. No search for such captures was carried out for this version of the record. The absence of a cited capture demonstrates neither their absence nor their existence.

## Strictly supported conclusion

- The expression "fidélité de reconstruction" appears in a revision of the article that Git dates 21 March 2026.
- The interpretive fidelity definition appears at its current paths in a revision that Git dates 9 May 2026, and the hosting provider's integration reports a successful deployment of that revision on the same day.
- The explicit terminological relationship is declared on 20 November 2026.
- These traces establish neither the content served on a past date, nor the first appearance of the expressions, nor an independent validation.
