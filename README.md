# SPIDER
SPIDER: a stacking-based ensemble learning framework for accurate prediction of druggable proteins.

## Dependency
The packages that this program depends on is 
`scikit-learn==0.24.1 or higher`. You can run following command in terminal.<br>
`pip install scikit-learn==0.24.1`

## How to use SPIDER
1. Copy your fasta file into `./input` and change the name to seq.fasta<br>
2. Run command<br>
`python spider.py`
3. The result including sequence Header, label and probability will be saved in `./output/predicted_result.csv`
