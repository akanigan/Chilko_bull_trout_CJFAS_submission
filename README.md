# Chilko_bull_trout_CJFAS_submission

## Reproducible environment (for reviewers)

### Requirements
- R (≥ 4.3 recommended). Tested on macOS (ARM). Should work on Windows/Linux.
- RStudio (≥ 2025.05.0+496) is recommended (it bundles Pandoc). If you use base R GUI, please install Pandoc separately.

### Steps

1) Download this repository as a ZIP and unzip it (do not alter the folder structure)
2) Open a fresh R session (don't load any .RData files). In R Studio: *File -> Open Project in New Session...* and select the unzipped project folder from where it was downloaded
3) In the console, run:
- install.packages("renv")
- renv::restore(prompt = FALSE)
- rmarkdown::render("CHILKO_BLTR_VPS.Rmd", clean=TRUE, envir=new.env())

This performs a test knit and produces an output file; however, the knit does not recompute analyses (see next step).

4) Open CHILKO_BLTR_VPS.Rmd from the project files directory and follow instructions within to replicate results


## License and Availability

The code and data provided here are made available **solely for the purposes of peer review** of the associated manuscript:

> cjfas-2025-0306: "Diel foraging behaviours of bull trout (<i>Salvelinus confluentus</i>) are altered by an annually deployed sockeye salmon (<i>Oncorhynchus nerka</i>) smolt counting fence"

They are **not licensed for redistribution or reuse** at this stage.

If the article is accepted for publication, the final version of both the code and data will be deposited in **Zenodo**, where they will receive a permanent DOI and be released under appropriate open licenses. At that time, the materials will be freely available for citation and reuse.
