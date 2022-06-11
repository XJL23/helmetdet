运行方式

训练：

python train.py --img 640 --batch 32 --epochs 100 --data data/helmet.ymal --weights weights/yolov5m.pt --cache

测试：

python detect.py --weights pt/best.pt --source data/images/--save-txt 


打开UI可视化面板

python main.py
