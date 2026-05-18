# CHANGELOG

## v2 (2026-05-17) — Doc 39 intake, counsel attribution, within-severity ordering

### Added
- **One new entry — F-87.** A federal filing not previously in the audit
  scope — Defendants' Response in Opposition to Plaintiff's Motion for
  Leave to File a Third Amended Complaint — was audited and added. The
  catalog now covers every substantive defense brief in both cases. **110
  entries — 86 federal, 24 Texas state** (was 109 — 85 / 24). The audit of
  that filing also verified all nine of its case citations against the
  opinion database; all resolved (no missing or misattributed cases), so
  the filing contributed exactly one entry.
- **Counsel of record, per filing.** Each entry's source filing is now
  identified with the attorney who signed it. Every defense filing
  catalogued here was signed by Scott D. Smith, Assistant Attorney General
  (Texas Bar No. 24011874), Office of the Attorney General of Texas — the
  detailed document shows a "Signed by" line on each entry, and the
  plain-language document names counsel once per Part. The attribution is
  established by each filing's own signature block, cited as provenance.

### Changed
- Within each severity band, entries are now listed in a fixed shuffled
  order rather than by entry number. The severity ordering is unchanged —
  most serious first (severity 4 → 1) within each Part. The plain-language
  and detailed documents share the same order, so they remain 1:1 aligned.

### Status
- **Staged for review, not yet published.** Unchanged from v1 — the catalog
  documents still carry a draft notice in their text.

## v1 (2026-05-17) — initial catalog

### Added
- **Litigation candor catalog** — accuracy audit of court filings in
  *Bass v. Texas Tech University Health Sciences Center* (N.D. Tex. No.
  5:25-cv-00244-H-BV; 237th Dist. Ct., Lubbock County, No.
  DC-2025-CV-1817). 109 entries — 85 federal, 24 Texas state.
- **`CANDOR_CATALOG_PLAIN_LANGUAGE.md`** — primary document; plain-language
  guide at Flesch-Kincaid grade 6.2.
- **`CANDOR_CATALOG_DETAILED.md`** — companion document; full legal version
  with rule citations, counter-cites, and the red-team test per entry.
- **`case_law/CASE_LAW_APPENDIX.md`** — case-law appendix. 52 case-law
  authorities and 7 statutes/court rules cited across the catalog;
  case name, court, year, and precedential status confirmed against a
  copy of the CourtListener opinion database (50 of 52 resolved; 2
  honestly flagged as not auto-resolved), with full-opinion links.
  `case_law/case_law_index.json` is the machine-readable index.
- Every entry passed an adversarial red-team pass: the strongest honest
  defense of the challenged wording was stated and tested against the
  primary source; only entries that still failed are kept.

### Changed
- Both catalog documents now list entries **by severity** — most serious
  first (severity 4 → 1) within each Part — instead of by entry number.
  Ties break by entry number ascending. The plain-language and detailed
  documents share the same sort, so they remain 1:1 aligned.
- The catalog audits the **defendants' filings and the state-court
  record**. A separate self-audit of the plaintiff's own filings is not
  part of this publication. Catalog credibility rests on the red-team
  test applied to every entry and on each entry quoting the exact filed
  language and naming its source, so any reader can verify it directly.

### Status
- **Staged for review, not yet published.** The catalog documents carry
  a draft notice in their text. Committed so the staged state can be
  reviewed before the repository is made public.
