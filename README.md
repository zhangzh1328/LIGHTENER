# LIGHTENER
## Requirements
- python : 3.8.17
- scanpy : 1.9.6
- sklearn : 1.2.2
- torch : 1.8.1
- torch-geometric : 2.2.0

## Datasets
- [Shekhar mouse retinca cells](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE81904)
- [Baron](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE84133)
- [10X PBMC](https://support.10xgenomics.com/single-cell-gene-expression/datasets/2.1.0/pbmc4k)
- [Camp](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE81252)
- [Mouse bladder cells](https://figshare.com/s/865e694ad06d5857db4b)
- [Zeisel](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE60361) 




## Run LIGHTENER
We take Baron dataset as an example 
```bash
python main.py --data_path './Baron.h5' --save_model_path './save_file' --n_clusters 14
```
 

