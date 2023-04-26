# GraphNN

## <ins>Dataset Info</ins>

These datasets used for node classification and transfer learning are Twitch user-user networks of gamers who stream in a certain language. Nodes are the users themselves and the links are mutual friendships between them. Vertex features are extracted based on the games played and liked, location and streaming habits. Datasets share the same set of node features, this makes transfer learning across networks possible. These social networks were collected in May 2018. The supervised task related to these networks is binary node classification - one has to predict whether a streamer uses explicit language.

#### Complete as many task as possible
1. Transfer learning
2. Binary node classification
3. Link prediction	
4. Community detection	
5. Network visualization


#### <ins>Folder meanings:</ins>
| Folder Code | Language             |
|------|---------------------|
| DE   | German              |
| ENGB | United Kingdom English |
| ES   | Spanish             |
| FR   | French              |
| PTBR | Portuguese          |
| RU   | Russian             |


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
