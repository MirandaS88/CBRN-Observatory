# Frontier AI-C(B)RN Commitments Observatory

A public record of what frontier AI companies commit to on chemical, biological, radiological and nuclear (CBRN) risks, with an initial focus on the biological domain, specifically.

The Observatory reads each company's published safety framework claim by claim and codes every claim to one codebook. The current crosswalk compares twelve frameworks from ten companies against the EU General-Purpose AI Code of Practice (Safety and Security chapter), and asks: do company frameworks commit to more on biology than the Code requires, or do they match its minimum?

**Web version:** [mirandas88.github.io/CBRN-Observatory](https://mirandas88.github.io/CBRN-Observatory/)

## What the crosswalk shows

- 52 of 67 bio-relevant claims name biology without saying anything specific about it.
- 28 of 67 treat the four CBRN domains as one undivided block, more than any other grouping.
- Nine of twelve frameworks set a biological capability threshold.
- Ten of twelve commit to publishing evaluation results, in general terms; none says anything specific about biology. Only Anthropic's Responsible Scaling Policy commits both to outside evaluation and to publishing it, and no framework sets out access terms for outside evaluators.

A depiction of addressed / partially addressed / not addressed on the crosswalk is a reading of what a published document says. It is not a compliance judgment nor a judgment about the company.

**Correction, 29 September 2026.** The Public transparency (Measure 10.2) and External evaluators (Appendix 3.5) columns previously counted only claims specific to biology, which showed no framework addressing either. Following mentor review, both are now read across the whole document, as Measures 8.1 and 1.3 already were. The printed poster shows the earlier version.

## Status

Working dataset v0.7.6 (25 September 2026). The coded dataset, codebook and version history will be released here with a DOI at v0.8.0, the first frozen version. Numbers on the web page may change before then.

## What is in this repository

| Path | What it is |
|---|---|
| `index.html` | The web version of the crosswalk, served at the address above |
| `archive-outdated/` | Coder reference tools for codebook v0.5.x. Outdated: kept for the record, not for use |

The dataset, codebook, scripts and coder tools aligned with the current codebook are added at v0.8.0.

## Scope and limits

- Published and publicly-accessible documents only. These cannot demonstrate implementation. Any information a company reports privately to the EU AI Office or to evaluators is not visible.
- Twelve frameworks are coded. Samsung Electronics and NAVER publish frameworks that carry no CBRN content; they were reviewed and recorded as documented nulls. Six companies that committed at the AI Seoul Summit (2024) to publish a framework have not, and are recorded as status records.
- Framework-wide infrastructure (security posture, incident response operations, legal and compliance machinery) is out of scope unless a measure is conditioned on a hazard-specific or capability-specific trigger. Measures that apply identically to every hazard by construction carry no signal about whether biological risk receives differentiated treatment, which is the research question.

## Licence

- Dataset, codebook, web page and documentation: [CC BY 4.0](LICENSE-DATA.md). Reuse and adapt them freely, with attribution.
- Scripts: [MIT](LICENSE).
- Verbatim quotations from company frameworks remain the property of their publishers and are reproduced for research and commentary. Neither licence covers them.

## Citing

Use the "Cite this repository" button on GitHub, or see [`CITATION.cff`](CITATION.cff). A DOI will be added at v0.8.0.

## Corrections and contact

Found an error in a coding or a quotation? Please open a [GitHub issue](https://github.com/MirandaS88/CBRN-Observatory/issues) with the framework, the section and what you think is wrong. For anything else: [LinkedIn](https://www.linkedin.com/in/miranda-smith-ab615a39/). ORCID: [0009-0001-5193-2516](https://orcid.org/0009-0001-5193-2516).

## Acknowledgements

Dr. Miranda Smith, Senior Fellow, was funded through the Pivotal Research Fellowship over the course of this work, with mentorship by Dr. Michael Mahar, Centre for Long-Term Resilience.
