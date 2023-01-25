# rMLST
A simple shell script which access rMLST species identification tool using PubMLST RESTful API.

## Installation
Only dependencies are **curl** and **jq**
```
git clone https://github.com/Kincekara/rMLST.git
```

## Usage
```
./rmlst.sh contigs.fasta
```

## Outputs
**rmlst.json** : A full output of the API as a json file<br>
**predicted_taxon.rmlst.txt** : A parsed text file including the predicted taxon

## Docker
A minimal docker (~5.5 MB) is available for containerized applications.
```
docker pull kincekara/rmlst:0.1
```
## References
Jolley, K. A., Bliss, C. M., Bennett, J. S., Bratcher, H. B., Brehony, C., Colles, F. M., Wimalarathna, H., Harrison, O. B., Sheppard, S. K., Cody, A. J., & Maiden, M. C. J. (2012). Ribosomal multilocus sequence typing: universal characterization of bacteria from domain to strain. Microbiology, 158(4), 1005–1015. https://doi.org/10.1099/mic.0.055459-0<br>
RESTful Application Programming Interface (API) — BIGSdb 1.39.0 documentation. (2023). Readthedocs.io. https://bigsdb.readthedocs.io/en/latest/rest.html#db-schemes-scheme-id-sequence‌<br>
rMLST Species identification via RESTful API. (2020). PubMLST. https://pubmlst.org/species-id/species-identification-via-api


‌
‌
