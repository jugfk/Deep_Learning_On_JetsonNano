# 젯슨 인퍼런스를 빌드하기 (Korean Version)
***
![image01](https://elinux.org/images/c/c7/Hello-AI-World-CV.png)

* Jetson Nano, TX1, TX2, Xavier

여러분의 젯슨 나노에서 터미널을 엽니다. (단축키: Ctrl + Alt + T)

(1) 다운로드하기
```
git clone https://github.com/dusty-nv/jetson-inference
cd jetson-inference
git submodule update --init
```

(2) 빌드트리 설정하기
```
mkdir build
cd build
cmake ../
```

(3) 빌드하기
```
make 
sudo make install
sudo ldconfig
```

(4) 실행하기

* Object Detection
```
cd /home/ubuntu/jetson-inference/build/aarch64/bin
python3 detectnet-camera.py
python3 imagenet-camera.py
python3 my-detection.py
```

* Image Detection 
```
chmod +x my-recognition.py
wget https://raw.githubusercontent.com/dusty-nv/jetson-inference/master/data/images/polar_bear.jpg
./my-recognition.py polar_bear.jpg

wget https://raw.githubusercontent.com/dusty-nv/jetson-inference/master/data/images/brown_bear.jpg
./my-recognition.py brown_bear.jpg
```


## 출처
* [Hello AI World](https://developer.nvidia.com/embedded/twodaystoademo)
* [오리지날 소스](https://github.com/dusty-nv/jetson-inference)
* [Jetson Zoo](https://elinux.org/Jetson_Zoo)
