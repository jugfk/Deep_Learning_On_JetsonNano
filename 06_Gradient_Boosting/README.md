# 그래디언트 부스팅 (Gradient Boosting) 
***

* 다운로드하기
```
git clone https://github.com/jetsonworld/Deep_Learning_On_JetsonNano.git
```

* 설치하기

(1) Scikit-Learn 그래디언트 부스팅 
```
sudo pip3 install scikit-learn
```
 
(2) LightGBM 그래디언트 부스팅
```
sudo pip3 install lightgbm
```

(3) xgboost 그래디언트 부스팅
```

```

 (설치하신분 있으시면 이매일 부탁드립니다. achasma@gmail.com)
* 실행하기
```
python3 00_Check_Versions.py
python3 01_Classification_Dataset.py
 ...
 ...
 ...
python3 07_LightGBM_for_Classification.py
Accuracy: 0.934 (0.021)
Prediction: 1
...
python3 08_LightGBM_for_Regression.py
MAE: -12.739 (1.408)
Prediction: -82.040
```

![LightGBM.png](https://raw.githubusercontent.com/jetsonworld/Deep_Learning_On_JetsonNano/master/06_Gradient_Boosting/LightGBM.png)

* References:
  * [Get Started with XGBoost](https://xgboost.readthedocs.io/en/latest/get_started.html)
  * [How To Install cmake on Ubuntu](https://tttsss77.tistory.com/77)
  * [Get the cmake Software](https://cmake.org/download/)
