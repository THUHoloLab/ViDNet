
# Training dataset

Authors: **[Yunhui Gao](https://github.com/Yunhui-Gao)** and **[Liangcai Cao](https://scholar.google.com/citations?user=FYYb_-wAAAAJ&hl=en)**


The released pretrained models have been trained on a dataset consisting of 70,405 five-frame *grayscale* video clips of natural dynamic scenes, which are extracted from the [DAVIS](https://davischallenge.org/) and [Vimeo-90K](http://toflow.csail.mit.edu/) database (please refer to the `meta_info.txt` files for details).

The directory and file structure for the dataset is shown below.
```
dataset/
├── DAVIS2017/
|   ├── Semi-Supervised-TrainVal/
|   |   ├── bear/
|   |   ├── bike-packing/
|   |   ├── ...
|   |   └── meta_info.txt
|   └── Semi-Supervised-Test-Dev/
|       ├── aerobatics/
|       ├── carousel/
|       ├── ...
|       └── meta_info.txt
└── Vimeo90K
    ├── 00001/
    |   ├── 0001/
    |   ├── 0002/
    |   ├── ...
    |   └── 1000/
    ├── 00002/
    |   ├── 0001/
    |   ├── 0002/
    |   ├── ...
    |   └── 1000/
    ├── ...
    └── meta_info.txt
```
