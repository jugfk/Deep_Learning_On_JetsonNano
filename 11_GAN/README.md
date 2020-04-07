# 생성 적대적 신경망 (GAN: Generative Adversarial Network)
***
* 다운로드하기
```
git clone https://github.com/jetsonworld/Deep_Learning_On_JetsonNano.git
cd Deep_Learning_On_JetsonNano/11_GAN
```

* 실행하기
```
python3 pytorch_gan_mnist.py

```
* 입력이미지

![image.jpeg](https://raw.githubusercontent.com/jetsonworld/Deep_Learning_On_JetsonNano/master/09_Deep_Learning_in_OpenCV/image.jpeg)

* 출력이미지

![basicFaceDetector.png](https://raw.githubusercontent.com/jetsonworld/Deep_Learning_On_JetsonNano/master/11_GAN/pytorh_gan_mnist_143.png)

***
# OpenCV에서 딥러닝(dnn)  
***
* frozen_inference_graph.pb 다운로드하기
```
cd Deep_Learning_On_JetsonNano/09_Deep_Learning_in_OpenCV
python3 download_gdrive.py 1uP9N5E2Jjm6-RrVwHLdBc00qQZeYH7Uj /home/ubuntu/Deep_Learning_On_JetsonNano/09_Deep_Learning_in_OpenCV/models/frozen_inference_graph.pb
```

* [main.py](https://raw.githubusercontent.com/jetsonworld/Deep_Learning_On_JetsonNano/09_Deep_Learning_in_OpenCV/main.py) 실행하기

```
python3 main.py
```
* 입력이미지

![image.jpeg](https://raw.githubusercontent.com/jetsonworld/Deep_Learning_On_JetsonNano/master/09_Deep_Learning_in_OpenCV/image.jpeg)

* 출력이미지

![main.png](https://raw.githubusercontent.com/jetsonworld/Deep_Learning_On_JetsonNano/master/09_Deep_Learning_in_OpenCV/main.png)
