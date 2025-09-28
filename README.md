# BoostGCN
*****
PyTorch implementation for:
> Revolutionizing Graph Aggregation: From Suppression to Amplification via BoostGCN 
> 
> Jian Xin Wu,Chenglong Pang, GuangXiong Chen, Jie Zhao*
> 
> NeurIPS 2025
## Datasets

This project provides the yelp2018 dataset for training and testing. 

Please download the data from the [Baidu Cloud:Yelp2018](https://pan.baidu.com/s/1I7sEa1opYfFr-TboKuUqTg?pwd=9y42)

Then, place the Data file in `/Data/Yelp2018/`
```
├─ Data/: 
    ├── yelp2018/:
        ├── test_data.npy           #test dataset,the number of negative samples is 1500
        ├── val_data.npy            #val dataset,the number of negative samples is 1500
        ├── train_user_pos_neg.npy  # val dataset(user,pos_item,neg_item)
        ├── train_log_i             # The weight file of the interaction edge
        ├── train_edge_index.npy    # the interaction edge
```
## Dependencies

```shell
pip install -r requirements.txt
```
* CUDA  11.8
* Python  3.8
* PyTorch  2.0.0
* torch-geometric  2.5.3



