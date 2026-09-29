# The L-E-F Model

**A three-dimensional model of political space**

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.23034027.svg)](https://doi.org/10.5281/zenodo.23034027)

(available only in Czech)

[Česká verze](README.cs.md)

---

## What this is

The L-E-F model describes politics as a three-dimensional space. It separates one
procedural axis from two substantive ones:

| Axis | Name | Negative pole | Positive pole |
|---|---|---|---|
| **L** | *liberté* | authoritarian (domination) | liberal (non-domination) |
| **E** | *égalité* | market, right | redistributive, left |
| **F** | *fraternité* | culturally closed | culturally open |

Contemporary measures of party positions collapse two distinct things into one
dimension: what a party wants to achieve, and whether it accepts the rules under
which such questions are decided. The widely used GAL-TAN scale mixes cultural
positions with attitudes towards the constraints on power, and thereby obscures
the mechanism by which democracies erode.

The L-E-F model separates them. It describes political space through three
orthogonal axes: **L** (*libertas*), a procedural axis grounded in the republican
concept of non-domination, measuring whether political competition is protected or
suppressed; **E** (*égalité*), the economic axis; and **F** (*fraternitas*), the
axis of cultural openness and closure. Only L is procedural: it does not say *what*
should be achieved but *how* decisions are made. E and F are substantive, and the
model takes no position on either.

From this the model derives a geometry. Parties are positions in a sphere and
distributions of voters around them; a society has a measurable *shape*, described
in three layers: the direction it leans in (the salience and polarity of each axis),
how far from the centre it reaches (depth), and how widely its voters are spread
(covariance). Two summary indicators follow: an index of polarisation, and an
authoritarian threshold expressing the claim that substantive extremity exerts
downward pressure on the procedural axis.

The unit of the model is the distribution of values among voters, weighted by votes,
not the distribution of seats. It asks not how power is divided, but what a society
holds.

The model is operationalised on existing data (CHES, MARPOR, V-Party, V-Dem) and
yields twenty-one testable hypotheses. The three documents below set out the
conceptual foundations, the formal apparatus and the measurement methodology, and
state openly which results are preliminary and which claims remain untested.

## Documents

| | Document | Question it answers |
|---|---|---|
| **A** | [Philosophical and social-science foundations](LEF_A_filozofie_a_spolecenskovedni_vychodiska.pdf) | *Why* three dimensions, what the axes mean, which hypotheses follow |
| **B** | [Geometry and mathematics](LEF_B_geometrie_a_matematika.pdf) | *How* positions and the shape of a society are computed |
| **C** | [Methodology, database and empirical testing](LEF_C1_metodologie.pdf) | *From what data* the model is computed and how it is tested |

## Documents

### A – Philosophical and social-science foundations
**Files:**  
- [PDF](LEF_A_filozofie_a_spolecenskovedni_vychodiska.pdf)  
- [DOCX](LEF_A_filozofie_a_spolecenskovedni_vychodiska.docx)

**Summary:**  
Explains why the model requires three dimensions and defines the meaning of axes L, E, and F.  
Develops the conceptual foundations, theoretical assumptions, and hypotheses about political space.  
Clarifies why axis L (liberté) is procedural and fundamentally different from E and F.

---

### B – Geometry and mathematics
**Files:**  
- [PDF](LEF_B_geometrie_a_matematika.pdf)  
- [DOCX](LEF_B_geometrie_a_matematika.docx)

**Summary:**  
Provides the mathematical framework for computing party positions and the shape of a society.  
Defines the geometry of the L‑E‑F space, distance metrics, transformations, and aggregation rules.  
Shows how societal leaning, reach, and dispersion are derived from individual or party-level data.

---

### C – Methodology, database and empirical testing
**Files:**  
- [PDF](LEF_C1_metodologie.pdf)  
- [DOCX](LEF_C1_metodologie.docx)

**Summary:**  
Describes the measurement pipeline and reconstruction rules for CHES, MARPOR, and V‑Party datasets.  
Documents the empirical validation strategy and known limitations (especially L–F discriminant validity).  
Includes the demonstration database and outlines the proposed purpose-built measurement instrument.

---

Each document can be read on its own. A complete single-volume version is also
available: [Politics as a three-dimensional space]([path]).

Documents are provided as PDF.

## Status

Work in progress. The conceptual and mathematical parts (A, B) are complete; the
methodology (C) is complete for the measurement pipeline and partially complete for
the test battery. The demonstration database reconstructs party positions from existing
expert and manifesto datasets; a purpose-built measurement instrument is proposed but
not yet fielded.

Results obtained so far are preliminary. Known limitations — most importantly the poor
discriminant validity of axes L and F in expert-survey data — are documented explicitly
in document C.

## Use of AI tools

The conception of the model, its theoretical foundations and all substantive
decisions are the author's own. A large language model (Claude, Anthropic) was
used in formalising the geometric and mathematical apparatus, in verifying claims
against the literature and the source datasets, and in drafting the text. The full
declaration is given at the end of each document. The author is responsible for
every claim made, including the verification of each calculation and each citation.

## Data sources

Party positions are reconstructed from **CHES**, **MARPOR/Manifesto Project** and
**V-Party**; electoral and government data from **ParlGov**; regime indicators from
**V-Dem** and its Episodes of Regime Transformation; validation data from **ESS** and
**WVS/EVS**. These datasets are not redistributed here; only the conversion rules and
derived values are.

## Citation

Zapletal, Jan (2026). *The L-E-F Model: A Three-Dimensional Model of Political Space*.
Zenodo. https://doi.org/10.5281/zenodo.23034027

This DOI represents all versions and always resolves to the latest one.

## Licence

Text and figures: [Creative Commons Attribution 4.0 International (CC BY 4.0)](LICENSE).
You may share and adapt the material, including commercially, provided you give credit.

## Contact

zapletal.jan@centrum.cz

## Keywords

political space, spatial models of politics, party positions, non-domination,
procedural democracy, democratic backsliding, autocratisation, hysteresis,
coalition formation, political cleavages, GAL-TAN critique, CHES, MARPOR, V-Party,
V-Dem, comparative politics, political theory
