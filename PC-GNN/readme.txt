# PC-GNN
Command lin argument:
python main.py --config ./config/pcgnn_amazon.yml

## Dataset

Amazon can be downloaded from (https://docs.dgl.ai/api/python/dgl.data.html#fraud-dataset).

Put them in `/data` directory and run `unzip /data/Amazon.zip` to unzip the datasets.


Run `python src/data_process.py` to pre-process the data.

## Requirements

```
argparse          1.1.0
networkx          1.11
numpy             1.16.4
scikit_learn      0.21rc2
scipy             1.2.1
torch             1.4.0
```
