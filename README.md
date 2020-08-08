# coco2yolo

[TOC]

## 1. coco2yolo
Converts MSCOCO dataset to Yolo format

将MS COCO数据集转换为Yolo格式

## 2. datset2coco

Converts the data in the given format to MSCOCO instance dataset

将给定格式的数据转换为coco instance数据集

    [
        {
            file_name: 图片名称
            width:  宽   
            height:  高
            annos: [
                        {
                            segmentation: 边界
                            area：  面积
                            bbox:   水平矩形框
                            iscrowd:    是否多个目标
                            category_id:    类别id
                        },
                    ]
        },
    ]


## 3. dota2coco
Converts DOTA dataset to  MSCOCO format

将DOTA数据集转换为MSCOCO格式

