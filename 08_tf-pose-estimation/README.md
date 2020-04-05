# 딥러닝 골격검출
***
(1) 다운로드 및 설치
```
git clone https://github.com/jetsonworld/tf-pose-estimation.git
cd tf-pose-estimation
sh install-tensorflow.sh
sh install-pose-estimation.sh
```

(2) 구동

- For Webcam:


```
python3 run_webcam.py --model=mobilenet_thin --resize=320x176
```

![image](https://raw.githubusercontent.com/jetsonworld/tf-pose-estimation/master/tf-pose-estimation.png)

## 출처
https://github.com/ildoonet/tf-pose-estimation

https://github.com/karaage0703/jetson-nano-tools

(Thank you for your precious devotion.)
