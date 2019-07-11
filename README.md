# SHNets
stacked hourglass nets in pytorch

## Commands
- Training
```
python train_classification.py --train-image-path ../FloorplanTransformation/pytorch/img_label_arr_train/ \
                               --val-image-path ../FloorplanTransformation/pytorch/img_label_arr_test/
```
```
python train_regression.py --augment --train-image-path ./data/ny_hei_train.txt \
                           --val-image-path ./data/ny_hei_val.txt
```

## Papers
- [Stacked Hourglass Networks for Human Pose Estimation, ECCV 2016](https://arxiv.org/pdf/1603.06937.pdf)
- [Stacked U-Nets: A No-Frills Approach to Natural Image Segmentation, 2018](https://arxiv.org/pdf/1804.10343.pdf)
- [Stacked U-Nets for Ground Material Segmentation in Remote Sensing Imagery, CVPRW, 2018](http://openaccess.thecvf.com/content_cvpr_2018_workshops/papers/w4/Ghosh_Stacked_U-Nets_for_CVPR_2018_paper.pdf)
