## 두 원의 위치관계를 묻는 문제

두 원의 위치관계는 7개의 경우로 나타낼 수 있다.


### 구현 Tips

두 원의 중심의 거리를 구하기위해 피타고라스의 정리가 사용된다.

피타고라스의 정리에는 root 가 들어가기 때문에 이를 프로그램으로 구현하기 위해선 부동소수점 연산을 사용해야 한다.

그러나, 부동 소수점 연산은 연산 결과의 오차를 포함하는 문제가 존재하기 때문에  영향을 미칠 수 있다.

이러한 문제를 해결하기 위해 거리를 구함에 있어 root 를 사용하지 않았다. 이를 고려하여 두 원의 반지름 길이의 차이와 합을 다룸에 있어서 제곱한 값을 이용한다.
