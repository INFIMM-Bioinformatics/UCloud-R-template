# Work on UCloud

## R 

### Renv

create a `.Renviron` in the project folder and write the line:

```
RENV_PATHS_CACHE=/work/Renv
```

### (Optional) Configure repository

create a `.Rprofile` in the project folder and write the line:

```
# Configure BioCManager to use Posit Package Manager:
options(BioC_mirror = "https://packagemanager.posit.co/bioconductor")
options(BIOCONDUCTOR_CONFIG_FILE = "https://packagemanager.posit.co/bioconductor/config.yaml")

# Configure a CRAN snapshot compatible with Bioconductor 3.19:
options(repos = c(CRAN = "https://packagemanager.posit.co/cran/__linux__/jammy/latest"))
```

## Python

Create a conda env.

## SevenBridges