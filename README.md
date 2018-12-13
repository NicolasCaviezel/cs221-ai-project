# Network Intrusion Detection
Stanford [CS221](http://web.stanford.edu/class/cs221/) Artificial Intelligence Project

## Installation
Install dependencies in `requirements.txt` for Python 3.6+:
```bash
pip install -r requirements.txt
```

## Downloading the dataset
The dataset is taken from the [UCI ML repository](http://kdd.ics.uci.edu/databases/kddcup99/kddcup99.html). Head over to that page and grab the `kddcup.data_10_percent.gz` file, uncompress, and place it at `resources/datasets/kddcup.data_10_percent`:
```
mkdir -p resources/datasets
wget -O - http://kdd.ics.uci.edu/databases/kddcup99/kddcup.data_10_percent.gz | gunzip -c > resources/datasets/kddcup.data_10_percent
```

## Running the experiments
Either run the `experiments.py` file as follows:
```bash
python experiments.py
```

Alternatively you can take a look at [`final.ipynb`](final.ipynb).

**Note:** experiments results are stored in the `results` folder. You can remove this folder to run everything from scratch. The experiments took less than 30 minutes to complete on a MacBook Pro 2.9 GHz Intel Core i7 with 16GB of memory. 

## Resources
- [Proposal](submissions/proposal.pdf)
- [Poster](submissions/poster.pdf)
- [Final report](submissions/final.pdf)
