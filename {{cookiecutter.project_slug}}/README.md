{{cookiecutter.project_slug}}
==============================

{{cookiecutter.project_short_description}}

Project Organization
--------------------

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
