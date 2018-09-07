Chemical Genomics of Tuberculosis
====================

A boilerplate for reproducible and transparent analysis of CGTB data with close resemblances to the philosophy of [Cookiecutter Data Science](https://github.com/drivendata/cookiecutter-data-science): *A logical, reasonably standardized, but flexible project structure for doing and sharing data science work.*

Requirements
------------
Install `cookiecutter` command line: `pip install cookiecutter`    

Usage
-----
To start a new science project:

`cookiecutter gh:eachanjohnson/cookiecutter-cgtb`

Project Structure
-----------------

```
.
├── AUTHORS.md
├── LICENSE
├── README.md
├── requirements.txt    <- Python dependences
├── snakeconfig.yml     <- Congifuration file for snakemake
├── Snakefile           <- Snakemake workflow for reproducibility
├── config/             <- Configuration files
├── data/               <- All input and output data
│   ├── interim/        <- Intermediate data that has been transformed.
│   ├── processed/      <- The final, canonical data sets for modeling.
│   └── raw/            <- The original, immutable data dump.
│       ├── annotations/<- Experimental metadata
│       └── sequencing/ <- FASTQ files
├── docs/               <- Documentation, e.g., doxygen or scientific papers (not tracked by git)
├── logs/               <- Logfiles from running utilities
│   └── snakemake/      <- Snakemake logs
├── models/             <- Serialized and fitted models
├── notebooks/          <- Jupyter notebooks
├── reports/            <- For a manuscript source, e.g., LaTeX, Markdown, etc., or any project reports
│   ├── figures/        <- Figures and plots arising from analysis
│   └── snakemake/      <- HTML reports from running snakemake
└── scripts/            <- R, Python, and cluster submission scripts
    ├── modeling/       <- Machine learning and statistics
    ├── processing/     <- Transforming raw into processed data
    ├── snakemake/      <- Snakemake scripts
    └── visualization/  <- visualization and figures
```

License
-------
This project is licensed under the terms of the [BSD License](/LICENSE)
