FROM rocker/verse:3.5.2

# Install linux pacakges for gsl 
RUN apt-get update && apt-get install -y \
    libgdal-dev \
    libproj-dev \
    libgsl-dev \
    libgsl2

# Install R packages from GitHub
RUN installGithub.r Joe-Hilgard/hilgard@bc2ab33

# Install CRAN packages
RUN install2.r acepack \
    BayesFactor \
    bdsmatrix \ 
    bindr \
    bindrcpp \ 
    censReg \ 
    checkmate \ 
    compute.es \ 
    estimability \ 
    Formula \ 
    glmmML \ 
    GPArotation \
    gridExtra \
    Hmisc \ 
    htmlTable \ 
    latticeExtra \
    lmtest \ 
    lsmeans \ 
    maxLik \ 
    miscTools \
    multcomp \ 
    ordinal \ 
    plm \ 
    polspline \
    psych \ 
    rms \ 
    sandwich \
    TH.data \
    ucminf \ 
    zoo \ 
    RSpectra

# Install here for my own script
RUN install2.r here

WORKDIR $HOME/rstudio