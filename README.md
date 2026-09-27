# Frontier AI-C(B)RN Commitments Observatory

A public record of what frontier AI companies actually commit to on chemical, biological, radiological and nuclear (CBRN) risk, with a close focus on biology.

The Observatory reads each company's published safety framework claim by claim and codes every claim to one codebook. The current crosswalk compares twelve frameworks from ten companies against the EU General-Purpose AI Code of Practice (Safety and Security chapter), and asks a simple question: do company frameworks commit to more on biology than the Code requires, or do they match its minimum?

**Web version:** [mirandas88.github.io/CBRN-Observatory](https://mirandas88.github.io/CBRN-Observatory/)

## What the crosswalk shows

- 52 of 67 bio-relevant claims name biology without saying anything specific about it.
- 28 of 67 treat the four CBRN domains as one undivided block, more than any other grouping.
- Nine of twelve frameworks set a biological capability threshold. None commits to publishing what its biological assessments find, and none fully sets out access terms for outside evaluators.

A mark on the crosswalk is a reading of what a published document says. It is not a compliance judgment, and not a judgment about the company.

## Status

Working dataset v0.7.6 (25 September 2026). The coded dataset, codebook and version history will be released here with a DOI at v0.8.0, the first frozen version. Numbers on the web page may change before then.

## What is in this repository

| Path | What it is |
|---|---|
| `index.html` | The web version of the crosswalk, served at the address above |
| `codebook_v0_5_*_coder_reference.html`, `guided_claim_check_v0_5_*.html` | Coder reference tools from an earlier codebook version, kept for the record |

The dataset, codebook and scripts are added at v0.8.0.

## Scope and limits

- Published documents only. They cannot show implementation, and anything a company reports privately to the EU AI Office or to evaluators is not visible from outside.
- Twelve frameworks are coded. Samsung Electronics and NAVER publish frameworks that carry no CBRN content; they were reviewed and recorded as documented nulls. Six companies that committed at the AI Seoul Summit (2024) to publish a framework have not, and are recorded as status records.
- Security mitigations are excluded, because they apply identically to every hazard.

## Licence

- Dataset, codebook, web page and documentation: [CC BY 4.0](LICENSE-DATA.md). Reuse and adapt them freely, with attribution.
- Scripts: [MIT](LICENSE).
- Verbatim quotations from company frameworks remain the property of their publishers and are reproduced for research and commentary. Neither licence covers them.

## Citing

Use the "Cite this repository" button on GitHub, or see [`CITATION.cff`](CITATION.cff). A DOI will be added at v0.8.0.

## Corrections and contact

Found an error in a coding or a quotation? Please open a [GitHub issue](https://github.com/MirandaS88/CBRN-Observatory/issues) with the framework, the section and what you think is wrong. For anything else: [LinkedIn](https://www.linkedin.com/in/miranda-smith-ab615a39/).

## Acknowledgements

Dr. Miranda Smith, Senior Fellow, was funded through the Pivotal Research Fellowship over the course of this work, with mentorship by Dr. Michael Mahar, Centre for Long-Term Resilience.
