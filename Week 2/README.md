# 이번 주 실습에 대한 고찰
### 배운 점
KNN은 예제 기반 학습 방법으로 최근접한 이웃 데이터를 범주로 넣는 알고리즘 방식이다.
이 때 사용자는 새로운 샘플을 넣으면 이 샘플로 부터 가까운 k개의 샘플을 추출해서 이 샘플이 어떤 집단에 속하는지 범주를 정하는 방식이다.
<br>

대부분의 데이터값은 중간값보다 한쪽으로 치우쳐진 값들이 많다는 점을 알게됨.
하지만 이 사이에도 결국 분산은 생길 수 밖에 없기 때문에, ideal fit 지점을 찾아야한다.<br>


### 앞으로 발전시켜야 할 점
이 ideal fit에 도달하기 위한 편향과 분산 사이를 찾는 방법에 대한 고찰이 필요해보인다.
즉 신뢰할 수 있는 모델이 과연 어떤 것인가에 대해서 다양한 데이터를 넣어보고 학습해가면서 공부할 필요가 있을것 같다.