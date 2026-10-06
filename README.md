# Lady Bird Deeds and Transfer on Death Deeds by State, 50 States and DC (2026)

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.23199404.svg)](https://doi.org/10.5281/zenodo.23199404)

For each of the 50 US states and the District of Columbia: whether a lady bird deed (enhanced life estate deed) has primary legal authority and of what kind (statute, court decision, Medicaid agency rule, or a court that declined it), whether a transfer on death or beneficiary deed statute exists with its citation, effective date and uniform-act status, what the instrument is called there, which instrument an owner there would use, and whether Medicaid estate recovery can reach a home passed by each deed.

**Canonical page and citation:** https://stepuplaw.com/data/lady-bird-deed-by-state/

## The counts, as of October 7, 2026

- **7 states** have authority for the lady bird deed: Rhode Island and Vermont by statute; Florida, Maryland, Michigan and Texas by court decision; North Carolina only in its Medicaid manual.
- **1 state** has said no: Iowa, whose Court of Appeals wrote in 2021 that Iowa is not one of the few states that have recognized enhanced life estate deeds (King v. Smith, No. 20-0137).
- **34 states plus DC** have a transfer on death deed statute (Maryland in force since October 1, 2026); 21 adopted the Uniform Real Property Transfer on Death Act; Arizona, Arkansas, Colorado and Missouri call it a beneficiary deed.
- **11 states** have neither instrument.
- Texas and Maryland have both.

The widely copied five-state list (Florida, Texas, Michigan, Vermont, West Virginia) is wrong in both directions: West Virginia has no authority for the deed, and Rhode Island, Maryland and North Carolina do.

## Method

Rows derive from the StepUpLaw Medicaid estate recovery and home-transfer deed dataset (verified September 23, 2026, corrected September 28, 2026; DOI 10.5281/zenodo.22922299), in which every cell was read against the state's own statute, decisions or Medicaid manual. On October 7, 2026 the court decisions were re-checked against a search of every court in a local copy of the CourtListener corpus (about ten million opinions) for the terms "lady bird deed", "ladybird deed" and "enhanced life estate", which returned 54 opinions: Michigan 29, Florida 8, Texas 8, Vermont 7, and one each from Iowa, Maine, Mississippi and an Illinois bankruptcy court, none from Rhode Island, Maryland or North Carolina. That sweep moved Texas from agency-rule to court-decision authority (Wright v. Jones, No. 10-21-00297-CV, Tex. App., Waco, July 26, 2023; Tex. HHSC v. Estate of Burt, No. 22-0437, Tex. May 3, 2024), rested Michigan on a published holding (Bill & Dena Brown Trust v. Garcia, 312 Mich. App. 684 (2015)), and recorded Iowa's refusal.

## Files

- `data/states.csv`, `data/states.json`: one row per jurisdiction, 51 rows, with the authority text, citations, dates and the pages read.
- `data/schema.json`: the column definitions and allowed values.

## Citation

Klagge, Kevin D., *Lady Bird Deeds and Transfer on Death Deeds by State, 50 States and DC (2026)*, StepUpLaw, https://stepuplaw.com/data/lady-bird-deed-by-state/ (DOI 10.5281/zenodo.23199404). Author ORCID: https://orcid.org/0009-0002-1385-8498.

## License

Released under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). This is reference data, not legal advice. Statutes change and courts read them differently; read the cited source and ask a lawyer licensed in the state before relying on any cell.
