```
pip install -r requirement.txt
```

```
$ python track.py --source test-drone-video  --yolo_model best.pt --save-vid
```

For new train weight

```
$ python train.py --img 640 --batch 16 --epochs 48 --data models/custom_yolov5.yaml --weights '' --cache

```

$ python train.py --img 640 --batch 16 --epochs 48 --data models/uav.yaml --weights uav.pt --cache

```

```
