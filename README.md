![Docker Cloud Automated build](https://img.shields.io/docker/cloud/automated/lcolling/odp-hilgard)
![Docker Cloud Build Status](https://img.shields.io/docker/cloud/build/lcolling/odp-hilgard)

![autobuild](https://github.com/ljcolling/odp-hilgard/workflows/autobuild/badge.svg)

Open data project repo for Hilgard et al (2019)

The built document can be view [here](https://git.colling.net.nz/odp-hilgard/)

## Manual instructions

To build this document manually, run the following steps

1. Download the data. 

```bash
make download 
```

2. Run the analysis 

```bash
make analysis
```
    
3. Compile the document

```bash
make document
```

## Dependencies 

[Docker desktop](https://www.docker.com/products/docker-desktop/)
