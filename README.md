# aiedu-engine
SNU 2022 AIEDU project, @samdochi

## Baseline
An Implementation of ~~~ in Pytorch for recommending university majors
- this repo built from [XXX's repo](https://github.com/younggyoseo/vae-cf-pytorch)
- [autoencoder model name should be inserted](https://arxiv.org/abs/1802.05814) is originated from Liang et al(2018)

## Difference
- movie arbitarty mapped to majors

## To replicae
- if you don't have data yet, download [ML-1M dataset](https://grouplens.org/datasets/movielens/) and locate it in project root dir
- and excute `python data.py`
- `python main.py --cuda` for full training
