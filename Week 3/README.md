# 이번 주 내용

### RMSE 함수
학습한 시간이 길어질수록 예측 점수와 실제 점수가 점점 올라가는 것을 확인할 수 있으며, 예측 점수보다 실제 점수가 더 높은 경우도 있음.

### 선형 회귀
KNN보다 선형회귀 방식이 성능이 좀 더 좋은 점을 확인할 수 있었음.
이를 실제 보스턴과 같은 데이터에 적용한 결과 또한 마찬가지였음을 확인할 수 있었다.

### 릿지 선형 모델
릿지의 경우에는 알파값이 높아질수록 훈련 성과가 떨어지는 점을 확인할 수 있다.
하지만 소수점으로 가면 반대로 훈련 성과가 높아지는 점을 확인할 수 있었다.

### 라쏘 선형 모델
이 경우 또한 알파값이 소숫점, 그리고 작아질 수록 성과가 높은 것을 확인할 수 있었다.

### 로지스텍 선형 모델
이 경우는 C 값이 높을 수록 훈련 데이터가 잘 나왔다. 특히 이 값이 10만이 넘어서니 정확도가 99퍼센트에 근접하게 나왔다.
