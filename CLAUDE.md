# AROS-Knowledge-Bank

Reference library for the AROS ecosystem: original papers, vendored inspiration codebases (`Projects/` submodules), the SkillOpt showcase pages, and the published MkDocs site (`mkdocs.yml` → GitHub Pages).

## Design Grounding

Before writing or changing anything a person sees, read the **LabOnoM Design Guide** (private repository `LabOnoM/design`, pinned here as version `2026.10.0` in `DESIGN_VERSION`): `DESIGN.md` at this repository's root is its family file "AROS Deep Space", verified by `scripts/design-pin-check.sh`; the family file itself is this product's profile (web and AROS surfaces); the guide's `GLOSSARY.md` holds every word on screen in English and Japanese, `STATES.md` every state a surface can be in, and `CONFORMANCE.md` the measured tests this repository keeps green. Design the change with the `ux-foundations` skill's P1 brief, audit the result with P2 and P3 in both themes, and record findings as clauses with tests. Tokens come from the guide, never pasted hex; status hues are reserved; no state is colour alone; words come from the glossary; every string ships in English and Japanese. For this repository that means the SkillOpt HTML pages and the MkDocs theming; the family token layer wins over local values. Never edit `DESIGN.md` here: propose the change in the guide.

Note: `Projects/` contains vendored third-party submodules with their own UIs and conventions — the family guideline does NOT apply to them.
