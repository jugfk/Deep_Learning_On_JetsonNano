# 생성 적대적 신경망 (GAN: Generative Adversarial Network)
***
* 다운로드하기
```
git clone https://github.com/jetsonworld/Deep_Learning_On_JetsonNano.git
cd Deep_Learning_On_JetsonNano/11_GAN
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

(2) [pytorch_gan_50_lines.py](https://raw.githubusercontent.com/jetsonworld/Deep_Learning_On_JetsonNano/master/11_GAN/pytorch_gan_50_lines.py)

* 실행하기
```
python3 pytorch_gan_50_lines.py
Epoch 0: D (0.5011895895004272 real_err, 0.9272026419639587 fake_err) G (0.5062749981880188 err); Real Dist ([3.9898060443401335, 1.2074305776572598]),  Fake Dist ([-0.6208501852750778, 0.04097929623658439]) 
Epoch 100: D (0.582051157951355 real_err, 0.5517983436584473 fake_err) G (0.8294881582260132 err); Real Dist ([3.9376606839895247, 1.2172945198092584]),  Fake Dist ([3.5044149293899536, 0.010991017860047674]) 
Epoch 200: D (0.5095553398132324 real_err, 0.4325638711452484 fake_err) G (0.8998678922653198 err); Real Dist ([3.972706045150757, 1.218285466201219]),  Fake Dist ([1.2324003615379333, 1.7495409925391034]) 
Epoch 300: D (0.681601881980896 real_err, 0.6487647891044617 fake_err) G (0.7347384691238403 err); Real Dist ([3.89955312846601, 1.2620796563709968]),  Fake Dist ([8.271864589214324, 3.844739144163884])
...
```

* 출력이미지

![pytorch_gan_50_lines_output.png](https://raw.githubusercontent.com/jetsonworld/Deep_Learning_On_JetsonNano/master/11_GAN/pytorch_gan_50_lines_output.png)
