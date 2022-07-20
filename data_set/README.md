## 使用指南
- 使用前要将该数据集需要放到yolov5的同级文件夹中,如
```angular2html
 parent
 ├── yolov5
 └── datasets
     └── coco128  ← downloads here (7 MB)
```
- 先执行**split_train_val.py** 用于在**ImageSets/Main**文件夹下生成train.txt,val.txt,trainval.txt三个文件存储训练，验证集的图片文件名
- **voc_label.py**用于在当前目录生成**labels**文件夹，以及train.txt,val.txt分别存储了图片的相对路径
