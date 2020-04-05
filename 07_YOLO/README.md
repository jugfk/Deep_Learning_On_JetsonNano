# 딥러닝 사물인식을 위한 YOLO v3 설치하기
***

* 젯슨 나노의 cuda 버젼 체크하기
```
$ cd /usr/local/
$ ls
```

* 기본으로 설치되어있는 CUDA Path를 export하기
```
$ export PATH=/usr/local/cuda-10.0/bin${PATH:+:${PATH}}
$ export LD_LIBRARY_PATH=/usr/local/cuda-10.0/lib64${LD_LIBRARY_PATH:+:${LD_LIBRARY_PATH}}
```

* darknet 프로젝트 YOLO를 다운로드하기
```
$ git clone https://github.com/AlexeyAB/darknet

$ cd darknet
$ wget https://pjreddie.com/media/files/yolov3.weights
$ wget https://pjreddie.com/media/files/yolov3-tiny.weights
```

* build를 위한 Makefile 설정하기
```
$ sudo vi Makefile
-------
GPU=1
CUDNN=1
OPENCV=1
-------
```

* Darknet YOLO build하기 <b>(1~2시간 소요)</b>
```
$ make
```

## 참고문헌
* [cuda와 OpenCV 컴파일하는 방법](https://pjreddie.com/darknet/install/#cuda)
* [YOLO v3: Real-Time Object Detection](https://pjreddie.com/darknet/yolo/)
* [YOLO v1 논문 (pdf): You Only Look Once: Unified, Real-Time Object Detection](https://pjreddie.com/media/files/papers/yolo_1.pdf)
* [YOLO v2 논문 (pdf): YOLO9000: Better, Faster, Stronger](https://pjreddie.com/media/files/papers/YOLO9000.pdf)
* [YOLO v3 논문 (pdf): YOLOv3: An Incremental Improvement](https://pjreddie.com/media/files/papers/YOLOv3.pdf)

(Thank you for your precious devotion.)
