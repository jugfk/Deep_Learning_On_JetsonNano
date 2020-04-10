# 강화학습 테트리스 게임
***

### 소개
[PYTORCH] Deep Q-learning for playing Tetris

다음은 에이전트가 Tetris를 플레이하도록 훈련시키기위한 파이썬 소스 코드입니다. 그것은 강화 학습의 응용 프로그램의 매우 기본적인 예라고 볼 수 있습니다.

* 설치 패키지
```
sudo pip3 install tensorboardX 
```

* 다운로드하기
```
git clone https://github.com/jetsonworld/Deep_Learning_On_JetsonNano.git
cd Deep_Learning_On_JetsonNano/12_Reinforcement_Learning
```

* [train.py](https://raw.githubusercontent.com/jetsonworld/Deep_Learning_On_JetsonNano/master/12_Reinforcement_Learning/train.py) 실행하기
```
python3 train.py
```

* [test.py](https://raw.githubusercontent.com/jetsonworld/Deep_Learning_On_JetsonNano/master/12_Reinforcement_Learning/test.py) 실행하기
```
python3 test.py
```


* 출력이미지

<p align="center">
  <img src="demo/tetris.gif" width=600><br/>
  <i>Tetris demo</i>
</p


![train.png](https://raw.githubusercontent.com/jetsonworld/Deep_Learning_On_JetsonNano/master/12_Reinforcement_Learning/train.png)

패키지 설치 요구사항

  * python 3.6
  * PIL
  * cv2
  * pytorch 
  * numpy
  * matplotlib
  

출처

[Tetris-deep-Q-learning-pytorch](https://github.com/uvipen/Tetris-deep-Q-learning-pytorch)

Thank you for your precious devotion.
