[![DOI](https://zenodo.org/badge/957867644.svg)](https://zenodo.org/badge/latestdoi/957867644)

# Descriptive review of already existing solutions, plans and policies regarding software marketplaces in NFDI consortia

> ✅ Deliverable 2.2 is finished! [30+ page PDF summary](https://github.com/KonradHoeffner/softwaresurvey/releases/latest/download/deliverable.pdf) and plots, and the tables are all available in the [release assets](https://github.com/KonradHoeffner/softwaresurvey/releases).

> 🚀  [Explore the data in the Juypter Notebook](https://github.com/KonradHoeffner/softwaresurvey/blob/master/results.ipynb)!

> ✍️ Are you also writing deliverables for nfdi.software? Use the [nfdi.software LaTeX template](https://codebase.helmholtz.cloud/nfdi.software/latex)!

> 💬  Any questions?
> Working for a different NFDI consortium and want to adapt the [LaTeX template](https://codebase.helmholtz.cloud/nfdi.software/latex)?
> Or you also want to conduct an NFDI survey and don't know how to start?
> Or you also want to use Juypter Notebook? Don't hesitate to contact me: [Konrad Höffner](https://www.imise.uni-leipzig.de/Mitarbeiter/Konrad_Hoeffner)!



## Abstract

The nfdi.software project surveyed the NFDI landscape (51 respondents from 23 out of 26 consortia) between March and April 2025 to understand the current state of software metadata and marketplaces.
Management, research, and software development roles were most represented.
Software dissemination primarily occurs through scientific publications and web pages.
The Citation File Format (CFF) is the preferred standard for describing research software metadata.
Regarding marketplaces, responses were split between having plans, wanting to stay informed without current plans, and having no interest.
A significant portion already links metadata to existing marketplaces.
Consortia prioritize active community involvement for sustainability.

## Rebuilding the PDF

### Requirements:

* local installation of Jupyter Notebook.
* LaTeX flavor that supports fontspec, so regular pdfLaTeX does not work (tested with tectonic based on XeTeX and TeXLive)

### Steps

1. Run all cells of the Juypter Notebook `results.ipynb` to generate the plots and tables.
2. Compile `deliverable.tex` to `deliverable.pdf`, e.g. `tectonic deliverable.tex` (exact command depends on your installed LaTeX engine)

## Licensing

We waive all copyright under the CC0 1.0 license but if you reuse or refer to our results it would still be nice if you [cite](CITATION.cff) the deliverable.

---

[nfdi.software](https://nfdi.software) is the basic service to provide a central marketplace to improve access to NFDI research software, addressing the needs of various scientific disciplines for sustainable research software use and development in development for the German National Research Data Infrastructure (Nationale Forschungsdateninfrastruktur—NFDI).
nfdi.software is part of and funded through Base4NFDI.
Funded by DFG as part of NFDI.
Grant Number: [521453681](https://gepris.dfg.de/gepris/projekt/521453681?context=projekt&task=showDetail&id=521453681&).
