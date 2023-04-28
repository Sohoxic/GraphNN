# GraphNN

## <ins>Dataset Info</ins>

This webgraph is a page-page graph of verified Facebook sites. Nodes represent official Facebook pages while the links are mutual likes between sites. Node features are extracted from the site descriptions that the page owners created to summarize the purpose of the site. This graph was collected through the Facebook Graph API in November 2017 and restricted to pages from 4 categories which are defined by Facebook. These categories are: politicians, governmental organizations, television shows and companies. The task related to this dataset is multi-class node classification for the 4 site categories.

#### Complete as many task as possible
1. Multi-class node classification	
2. Link prediction	
3. Community detection	
4. Network visualization



## <ins>Minimum Requirements</ins>

```
 networkx          2.4
 tqdm              4.28.1
 numpy             1.15.4
 pandas            0.23.4
 texttable         1.5.0
 scipy             1.1.0
 argparse          1.1.0
 gensim            3.6.0
```

## <ins>Installation commands if needed</ins>

 ```
  pip intall jupyternotebook
  pip intall networkx
  pip intall pytorch
  pip install torch-geometric
  pip install -q torch-scatter -f https://data.pyg.org/whl/torch-1.10.0+cu113.html
  pip install -q torch-sparse -f https://data.pyg.org/whl/torch-1.10.0+cu113.html
  pip install -q git+https://github.com/pyg-team/pytorch_geometric.git
  pip install --upgrade torch-cluster
 ```
 
 <ins>Repository Handlers</ins><br />
 [Arnav Kumar](https://github.com/ArnavKumar7)<br />
 [Vijith BG](https://github.com/crypto-vbg)
