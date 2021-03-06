## THIS APP REPOSITORY HAS BEEN PERMENANTLY MOVED TO [SEURATWIZARD](https://github.com/nasqar/SeuratWizard) AND IS NO LONGER MAINTAINED HERE
## PLEASE REFER TO NEW REPO FOR UPDATES AND DOCUMENTATION


---



# seuratOnline: R Shiny interface for Seurat single-cell analysis library


## Install:

```
devtools::install_github("aymanm/seuratOnline")
```

## Run:

```
library(seuratOnline)
seuratOnline()
```
This will run on http://0.0.0.0:1234/ by default

***

To run on specific ip/port:

```
ip = '127.0.0.1'
portNumber = 5555
seuratOnline(ip,portNumber)
```
This will run on http://127.0.0.1:5555/

## Screenshots:
![alt text](screenshots/screenshot-input.png "Input Data")

![alt text](screenshots/screenshot-vln.png "Vln Plots")

![alt text](screenshots/screenshot-biomarkers.png "Cluster Biomarkers")

## Acknowledgements:

1) Rahul Satija, Andrew Butler and Paul Hoffman (2017). Seurat: Tools for Single Cell Genomics. R package version 2.2.1\. [https://CRAN.R-project.org/package=Seurat](https://CRAN.R-project.org/package=Seurat)

2) [Satija Lab](http://satijalab.org/seurat/)
