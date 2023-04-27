## <div align="center">Install</div>

Clone repo and install [requirements.txt](https://github.com/ultralytics/yolov5/blob/master/requirements.txt) in a
[**Python>=3.7.0**](https://www.python.org/) environment, including
[**PyTorch>=1.7**](https://pytorch.org/get-started/locally/) with CUDA and cuDNN.

```bash
git clone https://github.com/Adamojlo119/PTI-Traffic-Sign-Recognition-Yolov5.git  # clone
cd PTI-Traffic-Sign-Recognition-Yolov5
pip install -r requirements.txt  # install
```

## <div align="center">Train</div>

```bash
py train.py --img 640 --data data/data.yaml --epochs 50 --weights '' --cfg models/yolov5s.yaml --batch-size 32 --cache ram
```
