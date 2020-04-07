# 강화학습 (Reinforcement Learning) (Korean Version)
***

### 소개

다음은 에이전트가 Tetris를 플레이하도록 훈련시키기위한 파이썬 소스 코드입니다. 그것은 강화 학습의 응용 프로그램의 매우 기본적인 예라고 볼 수 있습니다.

<p align="center">
  <img src="demo/tetris.gif" width=600><br/>
  <i>Tetris demo</i>
</p

* 다운로드하기
```
git clone https://github.com/jetsonworld/Deep_Learning_On_JetsonNano.git
cd Deep_Learning_On_JetsonNano/12_Reinforcement_Learning
```
(1) [pytorch_gan_mnist.py](https://raw.githubusercontent.com/jetsonworld/Deep_Learning_On_JetsonNano/master/11_GAN/pytorch_gan_mnist.py)

* 실행하기
```
python3 pytorch_gan_mnist.py
Epoch [0/200], Step [200/600], d_loss: 0.0409, g_loss: 4.0026, D(x): 0.99, D(G(z)): 0.03
Epoch [0/200], Step [400/600], d_loss: 0.0692, g_loss: 6.5672, D(x): 0.97, D(G(z)): 0.04
Epoch [0/200], Step [600/600], d_loss: 0.0449, g_loss: 4.7250, D(x): 0.99, D(G(z)): 0.03
Epoch [1/200], Step [200/600], d_loss: 0.0976, g_loss: 6.7460, D(x): 0.98, D(G(z)): 0.07
Epoch [1/200], Step [400/600], d_loss: 0.2162, g_loss: 4.1998, D(x): 0.91, D(G(z)): 0.05
Epoch [1/200], Step [600/600], d_loss: 0.2246, g_loss: 4.9113, D(x): 0.94, D(G(z)): 0.13
Epoch [2/200], Step [200/600], d_loss: 0.1410, g_loss: 4.1872, D(x): 0.94, D(G(z)): 0.04
Epoch [2/200], Step [400/600], d_loss: 0.2344, g_loss: 3.9755, D(x): 0.98, D(G(z)): 0.17
Epoch [2/200], Step [600/600], d_loss: 0.7069, g_loss: 3.3070, D(x): 0.84, D(G(z)): 0.24
Epoch [3/200], Step [200/600], d_loss: 0.2238, g_loss: 2.8475, D(x): 0.94, D(G(z)): 0.11
Epoch [3/200], Step [400/600], d_loss: 0.8142, g_loss: 2.7761, D(x): 0.77, D(G(z)): 0.22
Epoch [3/200], Step [600/600], d_loss: 1.4608, g_loss: 2.4249, D(x): 0.57, D(G(z)): 0.21
...
```
* 출력이미지

![basicFaceDetector.png](https://raw.githubusercontent.com/jetsonworld/Deep_Learning_On_JetsonNano/master/11_GAN/pytorh_gan_mnist_143.png)
