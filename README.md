# Tools for Gossip - Report

This is the report accompanying the [Tools for Gossip](https://github.com/RamonMeffert/tools-for-gossip) application.

## Compilation

All packages necessary for compilation are part of TeX Live. 
You need [`bibtex-tidy`](https://github.com/FlamingTempura/bibtex-tidy) if you want to clean and sort the `.bib` file.

```bash
# create a pdf
make
# clean up auxiliary files
make clean
# start a SyncTex session for live updates to the pdf
make preview 
# clean and sort the bibliography
make sources 
```